## Usage

1. Fork this repo
2. Go to Actions and click I understand my workflows, go ahead and enable them
3. Go to Settings -> Actions -> General -> Workflow permissions -> Choice Read and write permissions -> Click Save
4. Get a cookies using this [guide](https://github.com/yt-dlp/yt-dlp/wiki/FAQ#how-do-i-pass-cookies-to-yt-dlp)
5. Encode the cookies to base64
6. Add a secret called `COOKIES` using the encoded base64 at Settings -> Secrets and variables -> Actions -> New repository secret
7. Create a branch called `downloads`
8. Run the workflow with the vid url

> [!NOTE]
> Use the no cookies workflow for other websites
