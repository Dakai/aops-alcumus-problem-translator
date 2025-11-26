This userscript enhances the Art of Problem Solving (AoPS) Alcumus experience by adding a button that translates problem descriptions into Simplified Chinese, while preserving LaTeX formatting for mathematical notation.

Key features:

*   **Translation:** Translates the Alcumus problem text (including ALT text from images) to Simplified Chinese using the Gemini API (optional, requires API key) or the OpenRouter API.
*   **LaTeX Rendering:** Renders LaTeX mathematical notation within the translated text using MathJax, providing properly formatted equations and symbols.
*  **OpenRouter Fallback**: If the Gemini API service is temporarily unavailable due to overload, the script automatically fails over to provide translation using the models from OpenRouter.
*  **API Key Required**: To provide full functionality of the script, OpenRouter API Key is required.
*   **Easy to Use:** Adds a "Translate to Chinese" button directly on the Alcumus problem page.
*   **Accurate:** Leverages powerful translation and LaTeX rendering libraries for high-quality results. Improves learning and problem-solving accessibility for Chinese-speaking users.

To Use:
1. Install the userscript from GreasyFork.org [Link](https://greasyfork.org/en/scripts/557009-aops-alcumus-problem-translator)
2. **Important: Provide your OpenRouter API Key in the userscript source code.** It can optionally make use of your Google Gemini API Key if available and desired.
3. Visit an AoPS Alcumus problem page to see the translation button.
