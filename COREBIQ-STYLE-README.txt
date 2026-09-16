COREBIQ STYLE REFACTOR

All HTML files now link to the single shared stylesheet: style.corebiq

The stylesheet contains:
- CoreBIQ typography and font stack
- Global theme and colour tokens
- All extracted page/component CSS
- Former inline style declarations converted to CSS classes
- Dynamic role badge styles

No embedded <style> blocks remain in the HTML files.
