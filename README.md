# ublock-lists

Custom filter lists for [uBlock Origin](https://github.com/gorhill/uBlock).

## Lists

| List | Description |
| --- | --- |
| **Ratingless** | Hides ratings on IMDb, Letterboxd, Goodreads and EXT |
| **YouTube-Focus** | Hides Shorts, comments and recommendations on YouTube |

## Installation

1. Open the uBlock Origin dashboard and go to **Filter lists**.
2. Scroll to the bottom, expand **Import...**, and paste one or more of these URLs:

   ```
   https://raw.githubusercontent.com/neoduck0/ublock-lists/main/ratingless.txt
   https://raw.githubusercontent.com/neoduck0/ublock-lists/main/youtube-focus.txt
   ```

3. Click **Apply changes**.

## Contributing

Websites change their markup often, so selectors can stop working. If something is
no longer hidden (or something is hidden that shouldn't be), please
[open an issue](https://github.com/neoduck0/ublock-lists/issues) naming the site and
the page where it happens.

Pull requests are welcome. When you edit a list, bump the `! Version:` line in its header.

## License

[MIT](LICENSE)
