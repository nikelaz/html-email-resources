# HTML Email Developer Resources

## Snippets

- [Starter Boilerplate](https://github.com/nikelaz/html-email-resources/blob/main/snippets/starter.html)
- [Boilerplate Table](https://github.com/nikelaz/html-email-resources/blob/main/snippets/boilerplate-table.html)
- [Background Image on Table Cell](https://github.com/nikelaz/html-email-resources/blob/main/snippets/background-image.html)

## Tools

- [Buttons generator](https://buttons.cm)
- [Backgrounds generator](https://backgrounds.cm)

## Guidelines

### Responsive Images

- Set a fixed <strong>width</strong> as an HTML <strong>attribute</strong> for Outlook
- Set <strong>max-width</strong> and width to <strong>100%</strong> inline
- Set <strong>min-width</strong> to <strong>fixed px value</strong> inline

### Background Images

- Use the <strong>background attribute</strong> on <strong>td</strong>
- Use <strong>bgcolor attribute</strong> to provide a fallback color
- Add <strong>background inline style</strong> with fallback color and image url


### Accessibility

- Keep tables quiet using <strong>role="presentation"</strong>

### Layouts

- [Bulletproof Email Templates](https://jsnhall.github.io/bulletproof-email-template/)
  
### Table Layouts

- Ignore table headers, body, footer
- Restricts components to <strong>table</strong> <strong>tr</strong> <strong>td</strong>
- Place most styles on table cells (<strong>td</strong>)
- <strong>Padding</strong> is more reliable than <strong>margin</strong> on table cells
- Use the align property on table cells for horizontal alignment
- Do not use exact percentages (e.g. 50%-50%) in Outlook, rather use something like 48%-48% (it cannot calculate precisely)

### Responsive Layouts

- Media query sets container <strong>width: 100%;</strong> 
- Media query sets tables that serve as columns to <strong>display block;</strong> with <strong>width: 100%;</strong>

## Can I Use
- [CanIEmail](https://caniemail.com)
- [CampaignMonitor CSS](https://campaignmonitor.com/css)

## Testing Services

- [Cross-client testing (Litmus)](https://www.litmus.com)
- [Send yourself a test email](https://putsmail.com)

## Additional Resources

- [Ready-made components and compatibility tables](https://freshinbox.com)
- [Special markup language for emails](https://mjml.io)
- [Inky templating language for emails](https://foundation.zurb.com)
- [Maizzle templating language](https://maizzle.com)
- [Litmus Community](https://litmus.com/community)
- [Resources (TheBetter.Email)](https://thebetter.email/resources)
- [Target outlook using conditional comments](https://www.htmlemailcheck.com/knowledge-base/target-outlook-email-clients-using-conditional-comments)
- [Responsive grids with tables examples](https://litmus.com/builder/b4262aa)
