A theme to adjust a few things with the Discord UI refresh that I don't like.

# Using Other Themes
If you're using another theme with this, you might want to remove lines 1-11, 
as they hard code a few colors from the previous UI.

```CSS
/* Delete if using other themes */

.visual-refresh.theme-dark {
  --background-message-hover: #2f3036 !important;
}

.bar_c38106:not(.systemBar_c38106):not(:has(.channelTabs-trailing)) {
  background: #202225;
}

/* ^ Delete if using other themes ^ */
```
