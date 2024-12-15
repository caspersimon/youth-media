You will be given a source text about media and youth. Your task is to produce a summary following the instructions below. First, read all instructions carefully. After producing the final summary, at the very top of your output, provide three numbers:

1. The approximate number of words in the original source text (this can be given by the user or a rough estimate if not provided).  
2. The number of words in the main summary + any pre-expanded (“+”) callouts.  
3. The number of words in the main summary + all callouts (both pre-expanded and collapsed).

These word counts should appear before the code block and be clearly labeled. For example:

Words in original: ~XXXX words
Words in summary (main + pre-expanded): ~XXX words
Words in summary (main + all callouts): ~XXX words

If you cannot know the exact word count, you may estimate.

**Instructions for the Summary:**

1. **Structure and Headers:**
   - Convert all "####" headers from the source to "##" headers in the summary, keeping their text exactly the same and in the same order.
   - Italicized standalone lines from the source become "###" headers in the summary. You may paraphrase these h3 headers or merge them.
   - No extra blank line after any header.

2. **Length Guidelines:**
   - The main summary + any pre-expanded (“+”) callouts should be about 20% of the original text’s length.
   - With both pre-expanded (“+”) and collapsed (“-”) callouts included, the total length may be 35%-60% of the original text length.
   - If you have not been given the source length, you can assume a length and aim for reasonable proportions. For example, if the source is ~5,000 words, the main summary + pre-expanded callouts should be ~1,000 words (5,000\*0.2=1,000), and with all callouts included should be ~1,750 (5,000\*0.35) to ~3,000 (5,000\*0.6) words.

3. **Content and Nuance:**
   - Include important nuances (e.g., if effects are small, only apply to certain groups, or are contradicted by reanalysis).
   - If the text states an effect but not why, you may add a guess in parentheses ending with a question mark. Use guesses sparingly.

4. **Format and Readability:**
   - Use a mix of bullet points, short paragraphs, bold key phrases, and hierarchical headings (##, ###, ####) for scan-ability.
   - Add h4 headings or bold subheadings if helpful.
   - Keep the main text concise and scannable. Use callouts to provide extra details.

5. **Obsidian-Style Callouts:**
   - Use callouts for extra details, nuances, and deeper explanations:
     - `> [!info]+` for pre-expanded important context  
     - `> [!info]-` for collapsed details that count toward the 35%-60% length tier
     - `> [!tip]+`, `> [!warning]+`, etc., are also allowed.
   - Place callouts directly after the relevant bullet or paragraph.

6. **Output Formatting:**
   - After giving the three word counts at the top, produce the entire summary in a single fenced code block (```) so it can be easily copied.

**Think step-by-step before writing. Make sure the length approximations are consistent with the instructions. If needed, first estimate source length and adjust summary length accordingly.**
