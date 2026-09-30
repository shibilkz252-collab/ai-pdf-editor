NETLIFY DEPLOYMENT

1. Download and extract this ZIP.
2. Go to https://app.netlify.com/drop
3. IMPORTANT: Netlify Drop is suitable for static files, but Functions need a Netlify site deployment.
4. For easiest deployment, create a GitHub repository with this folder and import it into Netlify.
5. Build command: leave blank.
6. Publish directory: public
7. Functions directory: netlify/functions
8. Add environment variable OPENAI_API_KEY if AI is required.

This build is Netlify-compatible and does not expose an OpenAI key in browser JavaScript.

Note: Netlify Functions have execution limits. Large PDFs and advanced OCR/conversion may require a dedicated backend later.
