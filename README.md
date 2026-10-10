# Snake

[Русская версия](README.ru.md)

A browser Snake game styled after the screen of an old monochrome phone. Steer the snake to the apples, grow longer and do not run into yourself.

**[Play in the browser](https://posoxai.github.io/Snake/)**

<p>
  <img src="screenshots/day.png" width="300" alt="Snake in the light theme with the Russian interface: a long snake on a grey-green LCD field, heading for an apple">
  <img src="screenshots/night.png" width="300" alt="The same game in the dark theme with the English interface: the LCD field lit yellow-green on a dark case">
</p>

Left: the light theme with the Russian interface. Right: the dark theme with the English one.

## Rules

- The snake moves on its own on a 17 × 17 field. You only turn it.
- Every apple scores a point, makes the snake one cell longer and a little faster.
- After every fifth apple a blinking bonus appears for 6 seconds. It is worth 5 points.
- The game ends when the snake runs into a wall or into itself. The tail moves away on every step, so following your own tail closely is safe.
- The game is won if the snake fills the whole field.

## Settings

- **Speed:** slow, normal or fast. They start at 3, 5 and 8 cells a second.
- **Walls:** with the walls off the snake goes through the edge and comes out on the other side.

The best score is kept separately for each speed and wall setting. Changing either of them in the middle of a game asks once before the score is dropped.

## Controls

- Keyboard: arrow keys or W, A, S, D. Space, P or Esc pauses.
- Phone: swipe on the field the way to go, or use the pad under the field.
- Two quick turns between steps both count, so a U-turn in two presses works.

The game pauses by itself when you leave the tab. An unfinished game, the best scores and the settings are kept in the player's browser, and a reload brings the game back paused.

## Language

The interface is in English and Russian. It opens in Russian when Russian is among the browser's languages and in English otherwise. The RU/EN switch remembers your choice.

## How to run

The whole game is one file, `index.html`. There is no build step and there are no dependencies.

- Locally: open `index.html` in a browser.
- Online: the game is published with GitHub Pages at https://posoxai.github.io/Snake/. Every commit to `main` updates it automatically.

Fonts load from Google Fonts. Without a network the game falls back to system fonts.

## Visit counter

The published page counts visits with [GoatCounter](https://www.goatcounter.com/). According to the service, it sets no cookies and stores no personal data. The counter does not run when `index.html` is opened from disk.

## Credits

The game was written by Claude, the AI assistant made by Anthropic: the logic, the canvas graphics, the sound and the page design.

The rules are those of the classic Snake games. The look borrows the idea of a monochrome phone LCD; the drawings and the design of this version are its own.

The idea of making a browser version came from posoxAI.

## License

MIT. The full text is in [LICENSE](LICENSE).
