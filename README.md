# obsidian-web-clipper-templates

My personal collection of templates for the Obsidian Web Clipper plugin.

## Templates

- **[tweet.json](templates/tweet.json)**: This template embeds a tweet into a Markdown file.
- **[quote-tweet.json](templates/quote-tweet.json)**: This template embeds a quote tweet into a Markdown file.
- **[youtube.json](templates/youtube.json)**: This template extracts YouTube video details and its transcript into a Markdown file. See the usage guide below for details.

### Usage for `youtube.json`

This template requires the YouTube video's transcript to be visible on the page before clipping.

#### Steps

1.  Below the YouTube video description, click the **"...more"** button to expand the full description.
2.  Scroll to the bottom and click **"Show transcript"**.
3.  Once the transcript is visible on the page, clip it using the Obsidian Web Clipper.

Please refer to the images below. (I apologize that one screenshot is in Japanese.)

![Japanese screenshot showing the "Show transcript" button location.](https://github.com/user-attachments/assets/03b9b426-6020-4e91-8857-75cc80e32f3c)

In English, it looks like this:
![English screenshot showing the "Show transcript" button location.](https://github.com/user-attachments/assets/40e0808b-0ef0-4f76-a768-ec38f8e8e753)

#### Expected Result
The clipped result in Obsidian will look like this:

![Example of a clipped Markdown file in Obsidian.](https://github.com/user-attachments/assets/2d5fe940-82dd-49f0-ab38-e67a950f5582)

## Credits

The following features in `tweet.json` and `quote-tweet.json` are based on ideas from [Naoki Aoyama @naa0yama](https://x.com/naa0yama):

- Displaying images in their original resolution.
- Trimming trailing ellipses (`...`) from URLs.
