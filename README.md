## Usage

1. Fork this repo
2. Go to Actions and click I understand my workflows, go ahead and enable them
3. Get a cookies using this [guide](https://github.com/yt-dlp/yt-dlp/wiki/FAQ#how-do-i-pass-cookies-to-yt-dlp)
4. Encode the cookies to base64
5. Add a secret called `COOKIES` using the encoded base64 at Settings -> Secrets and variables -> Actions -> New repository secret
6. Create a branch called `downloads`
7. Run the workflow with the vid url

> [!NOTE]
> Use the no cookies workflow for other websites
