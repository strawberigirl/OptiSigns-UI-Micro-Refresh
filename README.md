# OptiSigns-UI-Micro-Refresh

## Figma Design File

[Designs and Prototype](https://strawberigirl.github.io/)

## GitHub Pages Live Preview

[Live Preview Link](https://strawberigirl.github.io/)

# Conversation Rationale

## Problem:

The original toolbar buttons functioned, but there were several UX and branding issues. Visually, the style felt mismatched with OptiSigns' brand identity it looked more like something you'd expect in a dark mode, even though the rest of the UI wasn't. The hierarchy was also inconsistent: several tools appeared in both the left panel and the top toolbar, which created confusion and redundancy.

Focus states weren’t always accurate. For example, selecting a tool in the top bar didn’t always remove the focus state from its counterpart in the left panel. This made it unclear which tool was active. A few buttons across the editor also reused the exact same icon and label, including the Photos and Images buttons, Elements and Shapes, and Text.

Additionally, there was no clear feedback when the icon was clicked a second time. Users would assume the panel would close, but nothing happened.

## Design decisions:

This redesign was approached with the idea that a more unified and consistent toolbar could reduce redundancy, improve clarity, and give users more usable space within the editor. The goal across all of these decisions was to reduce friction and improve user trust by making the interface feel more intentional, clean, and easy to scan.

**Hierarchy**: Consolidated toolbar layout (no duplicates e.g., “Elements,” “Photos,” “Images,” “Shapes”).

**Focus State**: Filled icons and bold labels now clearly show which tool is active, improving accessibility.

**Labeling & Icon Clarity**: More accurate labeling. (eg. Elements shouldn't only contain "Shapes + Elements")

**Color & Style**: All states match OptiSigns’ branding and meet WCAG 2.2 AA contrast requirements.

**Motion & Feedback**: Hover and active states now provide responsive visual feedback to improve usability.

## Conversion hypothesis:

If the toolbar buttons are refreshed to improve clarity, hierarchy, and branding consistency, users will navigate the editor more efficiently. This could lead to higher feature discovery, faster editing sessions, and lower friction for new users

## A/B Test Outline:

**Metric:**
CTR and usage rates of all toolbar buttons (e.g., how often each is clicked and interacted with).

**Sample Size Guess:**
~250 users per version.
This will give enough data to find a signifigant increase in interaction rate.

**Success Threshold:**
Around a 10-15% increase goal for confidence.
