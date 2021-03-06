# Random YouTube Comments

-   CLI Node App
-   Random winner generator of YouTube comments for giveaways

## Install

```Bash
git clone https://github.com/samnoh/random_youtube_comments_picker.git
cd random_youtube_comments
npm run build
npm i -g
```

## Requirements

-   Node.js & npm (or yarn)
-   You should have your own YouTube API key - [Link](https://developers.google.com/youtube/v3/getting-started)
-   Edit .env file before running

## .env

-   `API_KEY`: Your own YouTube API Key

## Usage

```Bash
youtube-comment <youtube url> [number of winners]
```

-   Pick up random winners and save their comments.
-   Or save all comments for data archiving purposes (`youtube-comment <youtube url>`).

#### Examples

-   Pick 7 winners

```Bash
youtube-comment https://www.youtube.com/watch?v=nNVMvXTOgkI 7
```

-   Download all comments

```Bash
youtube-comment https://www.youtube.com/watch?v=Rx9NoQ1uknI
```

## Uninstall

```Bash
npm rm -g random_youtube_comments_picker
```
