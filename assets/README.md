# Assets

This folder contains the icon files used by the Outlook add-in.

## Required Icons

The add-in requires the following icon sizes:
- `icon-16.png` - 16x16 pixels (used in ribbon)
- `icon-32.png` - 32x32 pixels (used in ribbon)
- `icon-64.png` - 64x64 pixels (high resolution)
- `icon-80.png` - 80x80 pixels (used in various UI elements)

## Creating Icons

### Design Guidelines

1. **Simple and recognizable**: Icons should be simple and clearly represent Zendesk integration
2. **Consistent style**: All sizes should use the same design
3. **Solid background**: Use a solid color background for better visibility
4. **Clear at small sizes**: Design should be clear even at 16x16

### Recommended Tools

- **Adobe Illustrator** - Professional vector graphics
- **Figma** - Free online design tool
- **GIMP** - Free image editor
- **Canva** - Easy-to-use online tool

### Color Suggestions

- **Zendesk Brand Colors**:
  - Primary: #03363D (dark teal)
  - Secondary: #17494D (teal)
  - Accent: #F8991D (orange)
- **Or use your organization's brand colors**

### Export Settings

- Format: PNG
- Color space: RGB
- Transparent background: Optional (solid background recommended for visibility)
- Quality: Maximum

## Current Icons

**⚠️ IMPORTANT:** The current icon files are placeholders and should be replaced with actual PNG images before deploying the add-in.

To replace the icons:
1. Create or obtain properly sized PNG files
2. Replace the placeholder files in this directory
3. Ensure filenames match exactly: `icon-16.png`, `icon-32.png`, `icon-64.png`, `icon-80.png`
4. Rebuild the add-in: `npm run build`

## Quick Icon Template

If you need a quick solution, you can:
1. Go to https://www.figma.com or https://www.canva.com
2. Create a new design with these dimensions
3. Add a simple "Z" letter with a ticket/envelope icon
4. Use Zendesk's teal color (#03363D)
5. Export each size as PNG

## Testing Icons

After replacing icons:
1. Clear Office cache
2. Restart the dev server: `npm run dev-server`
3. Reload Outlook
4. Check that icons appear correctly in the ribbon

## Resources

- [Office Add-in Icon Guidelines](https://docs.microsoft.com/en-us/office/dev/add-ins/design/add-in-icons)
- [Zendesk Brand Guidelines](https://www.zendesk.com/company/brand-guidelines/)
