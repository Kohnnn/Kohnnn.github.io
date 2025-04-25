# Blog Post Formatting and Style Guide

## 1. Overall Structure

Every blog post MUST adhere to the following structure:

1.  **Title (`# H1`):** Clear, concise, keyword-rich, and engaging. Title Case. Max 70 characters preferred.
2.  **Introduction:**
    *   Hook the reader.
    *   Briefly state the post's purpose and scope.
    *   Outline what the reader will learn or gain.
    *   (Optional) Include a relevant featured image immediately after the introduction.
3.  **Body:**
    *   Organize content logically using headings (`## H2`, `### H3`, etc.).
    *   Break down complex topics into smaller, digestible sections.
    *   Use paragraphs of reasonable length (typically 2-5 sentences).
4.  **Conclusion:**
    *   Summarize key takeaways.
    *   Offer final thoughts or recommendations.
    *   (Optional) Include a Call to Action (e.g., ask a question, suggest related reading).
5.  **AI Assistance Disclosure:** If AI was used significantly in drafting, include a brief, standardized disclosure statement at the end.
6.  **Disclaimer:** Include a standard financial/technical disclaimer if applicable (especially for investment or advice-related content).

## 2. Markdown Formatting Rules

*   **Headings:**
    *   Use `#` for the main title ONLY (H1).
    *   Use `##` for main section headings (H2).
    *   Use `###` for sub-section headings (H3).
    *   Use `####` for further sub-divisions (H4) if absolutely necessary. Avoid deeper nesting.
    *   Use Sentence case for H2, H3, H4 headings (Capitalize only the first word and proper nouns).
    *   Do NOT skip heading levels (e.g., don't go from H2 directly to H4).
*   **Emphasis:**
    *   Use `**bold**` for strong emphasis or highlighting key terms upon first use. Use sparingly.
    *   Use `*italic*` for mild emphasis, titles of works, or foreign words. Use sparingly.
    *   Avoid using bold or italics for entire sentences or paragraphs.
*   **Lists:**
    *   Use numbered lists (`1.`, `2.`, `3.`) for sequential steps or ordered items.
    *   Use bulleted lists (`*`, `-`, or `+`) for unordered items. Be consistent with the chosen bullet character within a list.
    *   Ensure proper indentation for nested lists.
*   **Links:**
    *   Use descriptive link text: `[Relevant Link Text](URL)`
    *   Avoid generic text like "click here".
    *   Verify all external links are functional and relevant. Open external links in a new tab where appropriate (platform dependent).
*   **Code:**
    *   Use `inline code snippets` using single backticks (\`) for variable names, commands, file names, short code examples, etc.
    *   Use fenced code blocks (```) for multi-line code examples. Specify the language for syntax highlighting (e.g., ```python, ```javascript, ```bash).
    ```python
    # Example Python code block
    def hello(name):
        print(f"Hello, {name}!")
    ```
*   **Blockquotes:**
    *   Use `> ` to quote external sources or highlight specific passages.
    *   Always attribute blockquotes. Example:
        > This is a quote from an external source.
        > -- Source Name
*   **Horizontal Rules:**
    *   Use `---` sparingly to create thematic breaks between major sections if needed, but headings are generally preferred.

## 3. Figures and Tables

*   **Numbering:** All figures and tables MUST be numbered sequentially throughout the post (Figure 1, Figure 2, Table 1, Table 2, etc.).
*   **Captions:**
    *   **Figures:** MUST have a descriptive caption *below* the figure. Format: `**Figure X:** Descriptive caption text.`
    *   **Tables:** MUST have a descriptive caption *above* the table. Format: `**Table X:** Descriptive caption text.`
*   **Formatting:**
    *   Use standard Markdown table syntax.
    *   Ensure tables are readable and not overly wide.
    *   Center images where possible (platform dependent).
*   **Alt Text:** All images (figures) MUST have descriptive `alt` text for accessibility and SEO. Describe the image content accurately and concisely.
*   **Notes/Sources:** If a figure or table requires source attribution or explanatory notes, add them *below* the caption (for tables) or below the figure+caption. Use italics or a smaller font size if possible. Format: `*Note: Data sourced from [Source Name/Link].*`

**Example Figure:**

```markdown
![Diagram showing cloud computing architecture](path/to/image.png)
**Figure 1:** A simplified overview of a typical cloud computing architecture, including front-end, back-end, and database layers.
*Note: Illustration based on common cloud service provider models.*


Example Table:

**Table 1:** Comparison of Common Investment Types

| Feature         | Stocks                     | Bonds                      | Real Estate                |
| --------------- | -------------------------- | -------------------------- | -------------------------- |
| **Risk Level**  | High                       | Low to Medium              | Medium to High             |
| **Potential Return** | High                   | Low to Medium              | Medium to High             |
| **Liquidity**   | High                       | Medium                     | Low                        |

*Note: Risk and return potential can vary significantly within each asset class.*

4. Content and Style

Tone: Professional, informative, objective, and accessible. Avoid overly casual language, slang, or hype.

Accuracy: ALL factual claims, data, statistics, and technical information MUST be accurate and verified. Cite sources for specific data points or claims.

Clarity: Explain complex concepts clearly. Define technical jargon or financial terms upon first use, or provide a glossary if needed. Use acronyms only after defining them first, e.g., "Return on Investment (ROI)".

Originality: While AI is used, the final content must be unique and provide value. Avoid direct plagiarism. Paraphrase, synthesize, and add original insights where possible. Human review and editing are mandatory.

Finance Specifics: Be cautious with financial advice. Clearly distinguish between educational information and direct recommendations (avoid giving direct recommendations unless qualified and licensed). Include necessary disclaimers.

Tech Specifics: Ensure code examples are correct and tested if possible. Specify versions or contexts where relevant (e.g., "This Python 3.9 code...").

5. Metadata

Categories: Assign ONE primary category per post. Choose from a predefined list (e.g., Finance, Technology, Investing, Software Development, Personal Finance, Cybersecurity).

Tags: Add 3-5 relevant tags per post. Tags should be more specific keywords reflecting the post's content (e.g., python, stock-market, AI, budgeting, cloud-computing, API). Use lowercase and hyphens for multi-word tags.

6. AI-Specific Guidelines

Verification: Crucially, all AI-generated content (facts, figures, code, explanations) MUST be fact-checked and verified by a human expert (you). AI can generate plausible-sounding but incorrect information (hallucinations).

Editing: AI output often requires significant editing for clarity, tone, flow, and accuracy to meet the standards outlined above.

Disclosure Statement (Example): Include a statement like this at the end of posts heavily drafted by AI:

*Disclosure: This post was drafted with the assistance of AI tools. It has been reviewed, edited, and verified by the author.*

Disclaimer (Example - Finance):

*Disclaimer: The information provided in this blog post is for educational purposes only and does not constitute financial advice. Consult with a qualified financial advisor before making any investment decisions.*

Disclaimer (Example - Technical):

*Disclaimer: Technical information and code examples are provided "as is" without warranty of any kind. Use at your own risk.*
