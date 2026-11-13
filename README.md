# Simple Inpaint

One HTML page. Upload a photo, paint a mask, type what you want there, download the result.

- Only the masked area changes. The AI result is cut by your mask (with a soft edge) and pasted onto the original photo, so everything outside the mask stays pixel-identical, at full resolution.
- Models: Gemini 3.1 Flash Image, Gemini 3 Pro Image, Gemini 2.5 Flash Image, GPT-5 Image Mini, GPT-5 Image, GPT-5.4 Image 2.
- Keys (stored only in your browser's localStorage): OpenRouter unlocks all models; a Google AI Studio key unlocks Gemini; an OpenAI key unlocks GPT Image (uses OpenAI's native mask endpoint).
- The button shows a rough price estimate; after a run via OpenRouter it shows the actual cost.
