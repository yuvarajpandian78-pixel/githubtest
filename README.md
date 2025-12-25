# githubtestata-color-mode=auto][data-light-theme*=light] {
        --color-workflow-card-bg: var(--bgColor-default);
        --color-workflow-card-header-shadow: rgba(0, 0, 0, 0);
        --color-bg-discussions-row-emoji-box: rgba(209, 213, 218, 0.5);
        --color-notifications-row-read-bg: var(--bgColor-muted);
        --color-notifications-row-bg: var(--bgColor-white);
        --color-user-mention-fg: var(--fgColor-default);
        --color-mktg-btn-shadow-outline: rgba(0, 0, 0, 0.15) 0 0 0 1px inset;
        --color-marketing-icon-primary: #218bff;
        --color-marketing-icon-secondary: #54aeff;
        --color-project-header-bg: #24292f;
        --color-project-sidebar-bg: var(--bgColor-white);
        --color-project-gradient-in: var(--bgColor-white);
        --color-project-gradient-out: rgba(255, 255, 255, 0);
        --color-diff-blob-selected-line-highlight-mix-blend-mode: multiply;
        --color-text-white: var(--fgColor-white);
    }
}
@media (prefers-color-scheme: light) {
    [data-color-mode=auto][data-light-theme*=light] {
        color-scheme: light;
    }
}
[data-color-mode="light"][data-light-theme="light"], [data-color-mode="light"][data-light-theme="light"] ::backdrop, [data-color-mode="auto"][data-light-theme="light"], [data-color-mode="auto"][data-light-theme="light"] ::backdrop {
    --bgColor-success-emphasis: #1f883d;
    --button-outline-bgColor-active: #0757ba;
    --button-primary-bgColor-active: #197935;
    --button-primary-bgColor-disabled: #95d8a6;
    --button-primary-bgColor-hover: #1c8139;
    --buttonCounter-danger-fgColor-rest: #c21c2c;
    --color-ansi-cyan: #1b7c83;
    --color-ansi-cyan-bright: #3192aa;
    --control-checked-bgColor-active: #0757ba;
    --control-checked-bgColor-hover: #0860ca;
    --fgColor-danger: #d1242f;
    --reactionButton-selected-bgColor-hover: #caecff;
    --avatarStack-fade-bgColor-default: #c8d1da;
    --avatarStack-fade-bgColor-muted: #dae0e7;
    --bgColor-accent-emphasis: #0969da;
    --bgColor-accent-muted: #ddf4ff;
    --bgColor-attention-emphasis: #9a6700;
    --bgColor-attention-muted: #fff8c5;
    --bgColor-danger-emphasis: #cf222e;
    --bgColor-danger-muted: #ffebe9;
    --bgColor-disabled: #eff2f5;
    --bgColor-done-emphasis: #8250df;
    --bgColor-done-muted: #fbefff;
    --bgColor-emphasis: #25292e;
    --bgColor-inverse: #25292e;
    --bgColor-muted: #f6f8fa;
    --bgColor-neutral-emphasis: #59636e;
    --bgColor-neutral-muted: #818b981f;
    --bgColor-open-emphasis: var(--bgColor-success-emphasis);
    --bgColor-severe-emphasis: #bc4c00;
    --bgColor-severe-muted: #fff1e5;
    --bgColor-sponsors-emphasis: #bf3989;
    --bgColor-sponsors-muted: #ffeff7;
    --bgColor-success-muted: #dafbe1;
    --bgColor-transparent: #ffffff00;
    --borderColor-accent-emphasis: #0969da;
    --borderColor-accent-muted: #54aeff66;
    --borderColor-attention-emphasis: #9a6700;
    --borderColor-attention-muted: #d4a72c66;
    --borderColor-danger-emphasis: #cf222e;
    --borderColor-danger-muted: #ff818266;
    --borderColor-default: #d1d9e0;
    --borderColor-disabled: #818b981a;
    --borderColor-done-emphasis: #8250df;
    --borderColor-done-muted: #c297ff66;
    --borderColor-emphasis: #818b98;
    --borderColor-neutral-emphasis: #59636e;
    --borderColor-severe-emphasis: #bc4c00;
    --borderColor-severe-muted: #fb8f4466;
    --borderColor-sponsors-emphasis: #bf3989;
Show all properties (844 more)
}
:root {
    --blame-segments-count: 1;
    --blame-virt-total-size: unset;
    --blame-single-blame-height-narrow: 41px;
}
:root {
    --line-number-cell-width: 44px;
    --line-number-cell-width-unified: 88px;
    --diff-line-minimum-height: 24px;
    --diff-line-height: 24px;
    --diff-action-bar-position: 0;
}
:root {
    --pr-toolbar-sticky-header-height: max(var(--observed-header-height, 60px), 60px);
}
:root, [data-color-mode=light][data-light-theme*=light], [data-color-mode=dark][data-dark-theme*=light] {
    --color-workflow-card-bg: var(--bgColor-default);
    --color-workflow-card-header-shadow: rgba(0, 0, 0, 0);
    --color-bg-discussions-row-emoji-box: rgba(209, 213, 218, 0.5);
    --color-notifications-row-read-bg: var(--bgColor-muted);
    --color-notifications-row-bg: var(--bgColor-white);
    --color-user-mention-fg: var(--fgColor-default);
    --color-mktg-btn-shadow-outline: rgba(0, 0, 0, 0.15) 0 0 0 1px inset;
    --color-marketing-icon-primary: #218bff;
    --color-marketing-icon-secondary: #54aeff;
    --color-project-header-bg: #24292f;
    --color-project-sidebar-bg: var(--bgColor-white);
    --color-project-gradient-in: var(--bgColor-white);
    --color-project-gradient-out: rgba(255, 255, 255, 0);
    --color-diff-blob-selected-line-highlight-mix-blend-mode: multiply;
    --color-text-white: var(--fgColor-white);
}
:root {
    --duration-fast: 80ms;
    --easing-easeInOut: cubic-bezier(0.65, 0, 0.35, 1);
}
:root {
    --actionListContent-paddingBlock: var(--control-medium-paddingBlock);
}
:root {
    --Layout-pane-width: 220px;
    --Layout-content-width: 100%;
    --Layout-template-columns: 1fr var(--Layout-pane-width);
    --Layout-template-areas: "content pane";
    --Layout-column-gap: var(--base-size-16);
    --Layout-row-gap: var(--base-size-16);
    --Layout-outer-spacing-x: 0px;
    --Layout-outer-spacing-y: 0px;
    --Layout-inner-spacing-min: 0px;
    --Layout-inner-spacing-max: 0px;
}
[data-color-mode] {
    color: var(--fgColor-default, var(--color-fg-default));
    background-color: var(--bgColor-default, var(--color-canvas-default));
}
:root, [data-color-mode=light][data-light-theme*=light], [data-color-mode=dark][data-dark-theme*=light] {
    color-scheme: light;
}
:root {
    --h00-size-mobile: 2.5rem;
    --h0-size-mobile: 2rem;
    --h1-size-mobile: 1.625rem;
    --h2-size-mobile: 1.375rem;
    --h3-size-mobile: 1.125rem;
    --h00-size: 3rem;
    --h0-size: 2.5rem;
    --h1-size: 2rem;
    --h2-size: 1.5rem;
    --h3-size: 1.25rem;
    --h4-size: 1rem;
    --h5-size: 0.875rem;
    --h6-size: 0.75rem;
    --body-font-size: 0.875rem;
    --font-size-small: 0.75rem;
}
:root {
    --fontStack-monospace: ui-monospace, SFMono-Regular, SF Mono, Menlo, Consolas, Liberation Mono, monospace;
    --fontStack-sansSerif: -apple-system, BlinkMacSystemFont, "Segoe UI", "Noto Sans", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji";
    --fontStack-sansSerifDisplay: -apple-system, BlinkMacSystemFont, "Segoe UI", "Noto Sans", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji";
    --fontStack-system: -apple-system, BlinkMacSystemFont, "Segoe UI", "Noto Sans", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji";
    --text-body-lineHeight-large: 1.5;
    --text-body-lineHeight-medium: 1.42857;
    --text-body-lineHeight-small: 1.66667;
    --text-body-size-large: 1rem;
    --text-body-size-medium: 0.875rem;
    --text-body-size-small: 0.75rem;
    --text-caption-lineHeight: 1.3333;
    --text-caption-size: 0.75rem;
    --text-codeBlock-lineHeight: 1.5385;
    --text-codeBlock-size: 0.8125rem;
    --text-codeInline-size: 0.9285em;
    --text-display-lineBoxHeight: 1.4;
    --text-display-lineHeight: 1.4;
    --text-display-size: 2.5rem;
    --text-subtitle-lineHeight: 1.6;
    --text-subtitle-size: 1.25rem;
    --text-title-lineHeight-large: 1.5;
    --text-title-lineHeight-medium: 1.6;
    --text-title-lineHeight-small: 1.5;
    --text-title-size-large: 2rem;
    --text-title-size-medium: 1.25rem;
    --text-title-size-small: 1rem;
    --text-body-weight: var(--base-text-weight-normal);
    --text-caption-weight: var(--base-text-weight-normal);
    --text-codeBlock-weight: var(--base-text-weight-normal);
    --text-codeInline-weight: var(--base-text-weight-normal);
    --text-display-weight: var(--base-text-weight-medium);
    --text-subtitle-weight: var(--base-text-weight-normal);
    --text-title-weight-large: var(--base-text-weight-semibold);
    --text-title-weight-medium: var(--base-text-weight-semibold);
    --text-title-weight-small: var(--base-text-weight-semibold);
    --text-body-shorthand-large: var(--text-body-weight) var(--text-body-size-large) / var(--text-body-lineHeight-large) var(--fontStack-sansSerif);
    --text-body-shorthand-medium: var(--text-body-weight) var(--text-body-size-medium) / var(--text-body-lineHeight-medium) var(--fontStack-sansSerif);
    --text-body-shorthand-small: var(--text-body-weight) var(--text-body-size-small) / var(--text-body-lineHeight-small) var(--fontStack-sansSerif);
    --text-caption-shorthand: var(--text-caption-weight) var(--text-caption-size) / var(--text-caption-lineHeight) var(--fontStack-sansSerif);
    --text-codeBlock-shorthand: var(--text-codeBlock-weight) var(--text-codeBlock-size) / var(--text-codeBlock-lineHeight) var(--fontStack-monospace);
    --text-codeInline-shorthand: var(--text-codeInline-weight) var(--text-codeInline-size) var(--fontStack-monospace);
    --text-display-shorthand: var(--text-display-weight) var(--text-display-size) / var(--text-display-lineHeight) var(--fontStack-sansSerifDisplay);
    --text-subtitle-shorthand: var(--text-subtitle-weight) var(--text-subtitle-size) / var(--text-subtitle-lineHeight) var(--fontStack-sansSerifDisplay);
    --text-title-shorthand-large: var(--text-title-weight-large) var(--text-title-size-large) / var(--text-title-lineHeight-large) var(--fontStack-sansSerifDisplay);
    --text-title-shorthand-medium: var(--text-title-weight-medium) var(--text-title-size-medium) / var(--text-title-lineHeight-medium) var(--fontStack-sansSerifDisplay);
    --text-title-shorthand-small: var(--text-title-weight-small) var(--text-title-size-small) / var(--text-title-lineHeight-small) var(--fontStack-sansSerif);
}
:root {
    --control-large-paddingBlock: 0.625rem;
    --control-medium-paddingBlock: 0.375rem;
    --control-xlarge-paddingBlock: 0.875rem;
    --control-xsmall-paddingBlock: 0.125rem;
    --overlay-height-large: 27rem;
    --overlay-height-medium: 20rem;
    --overlay-height-small: 16rem;
    --overlay-height-xlarge: 37.5rem;
    --overlay-offset: 0.25rem;
    --overlay-width-large: 40rem;
    --overlay-width-medium: 30rem;
    --overlay-width-small: 20rem;
    --overlay-width-xlarge: 60rem;
    --overlay-width-xsmall: 12rem;
    --spinner-strokeWidth-default: 0.125rem;
    --control-large-gap: 0.5rem;
    --control-large-lineBoxHeight: 1.25rem;
    --control-large-paddingInline-normal: 0.75rem;
    --control-large-paddingInline-spacious: 1rem;
    --control-large-size: 2.5rem;
    --control-medium-gap: 0.5rem;
    --control-medium-lineBoxHeight: 1.25rem;
    --control-medium-paddingInline-condensed: 0.5rem;
    --control-medium-paddingInline-normal: 0.75rem;
    --control-medium-paddingInline-spacious: 1rem;
    --control-medium-size: 2rem;
    --control-minTarget-coarse: 2.75rem;
    --control-minTarget-fine: 1rem;
    --control-small-gap: 0.25rem;
    --control-small-lineBoxHeight: 1.25rem;
    --control-small-paddingBlock: 0.25rem;
    --control-small-paddingInline-condensed: 0.5rem;
    --control-small-paddingInline-normal: 0.75rem;
    --control-small-size: 1.75rem;
    --control-xlarge-gap: 0.5rem;
    --control-xlarge-lineBoxHeight: 1.25rem;
    --control-xlarge-paddingInline-normal: 0.75rem;
    --control-xlarge-paddingInline-spacious: 1rem;
    --control-xlarge-size: 3rem;
    --control-xsmall-gap: 0.25rem;
    --control-xsmall-lineBoxHeight: 1.25rem;
    --control-xsmall-paddingInline-condensed: 0.25rem;
    --control-xsmall-paddingInline-normal: 0.5rem;
    --control-xsmall-paddingInline-spacious: 0.75rem;
    --control-xsmall-size: 1.5rem;
    --controlStack-large-gap-auto: 0.5rem;
    --controlStack-large-gap-condensed: 0.5rem;
    --controlStack-large-gap-spacious: 0.75rem;
    --controlStack-medium-gap-condensed: 0.5rem;
    --controlStack-medium-gap-spacious: 0.75rem;
Show all properties (16 more)
}
@media (pointer: fine) {
    :root {
        --control-minTarget-auto: 1rem;
        --controlStack-medium-gap-auto: 0.5rem;
        --controlStack-small-gap-auto: 0.5rem;
    }
}
:root {
    --breakpoint-large: 63.25rem;
    --breakpoint-medium: 48rem;
    --breakpoint-small: 34rem;
    --breakpoint-xlarge: 80rem;
    --breakpoint-xsmall: 20rem;
    --breakpoint-xxlarge: 87.5rem;
}
:root {
    --borderRadius-full: 624.9375rem;
    --borderRadius-large: 0.75rem;
    --borderRadius-medium: 0.375rem;
    --borderRadius-small: 0.1875rem;
    --borderWidth-thick: 0.125rem;
    --borderWidth-thicker: 0.25rem;
    --borderWidth-thin: 0.0625rem;
    --outline-focus-offset: -0.125rem;
    --outline-focus-width: 0.125rem;
    --borderRadius-default: var(--borderRadius-medium);
    --borderWidth-default: var(--borderWidth-thin);
    --boxShadow-thick: inset 0 0 0 var(--borderWidth-thick);
    --boxShadow-thicker: inset 0 0 0 var(--borderWidth-thicker);
    --boxShadow-thin: inset 0 0 0 var(--borderWidth-thin);
}
:root {
    --base-text-weight-light: 300;
    --base-text-weight-medium: 500;
    --base-text-weight-normal: 400;
    --base-text-weight-semibold: 600;
}
:root {
    --base-size-112: 7rem;
    --base-size-12: 0.75rem;
    --base-size-128: 8rem;
    --base-size-16: 1rem;
    --base-size-2: 0.125rem;
    --base-size-20: 1.25rem;
    --base-size-24: 1.5rem;
    --base-size-28: 1.75rem;
    --base-size-32: 2rem;
    --base-size-36: 2.25rem;
    --base-size-4: 0.25rem;
    --base-size-40: 2.5rem;
    --base-size-44: 2.75rem;
    --base-size-48: 3rem;
    --base-size-6: 0.375rem;
    --base-size-64: 4rem;
    --base-size-8: 0.5rem;
    --base-size-80: 5rem;
    --base-size-96: 6rem;
}
:root {
    --base-duration-0: 0ms;
    --base-duration-100: 100ms;
    --base-duration-1000: 1s;
    --base-duration-200: 200ms;
    --base-duration-300: 300ms;
    --base-duration-400: 400ms;
    --base-duration-50: 50ms;
    --base-duration-500: 500ms;
    --base-duration-600: 600ms;
    --base-duration-700: 700ms;
    --base-duration-800: 800ms;
    --base-duration-900: 900ms;
    --base-easing-easeIn: cubic-bezier(0.7, 0.1, 0.75, 0.9);
    --base-easing-easeInOut: cubic-bezier(0.6, 0, 0.2, 1);
    --base-easing-easeOut: cubic-bezier(0.3, 0.8, 0.6, 1);
    --base-easing-linear: cubic-bezier(0, 0, 1, 1);
}
:root {
    --tab-size-preference: 4;
}
:root {
    --fontStack-monospace: "Monaspace Neon", ui-monospace, SFMono-Regular, SF Mono, Menlo, Consolas, Liberation Mono, monospace !important;
}
@media (prefers-color-scheme: light) {
    [data-color-mode=auto][data-light-theme*=light] {
        --csstools-color-scheme--light: initial;
        color-scheme: light;
    }
}
@media (prefers-color-scheme: light) {
    [data-color-mode=auto][data-light-theme*=light] {
        --csstools-color-scheme--light: initial;
        color-scheme: light;
    }
}
@media (prefers-color-scheme: light) {
    [data-color-mode=auto][data-light-theme*=light] {
        --csstools-color-scheme--light: initial;
        color-scheme: light;
    }
}
@media (prefers-color-scheme: light) {
    [data-color-mode=auto][data-light-theme*=light] {
        --csstools-color-scheme--light: initial;
        color-scheme: light;
    }
}
@media (prefers-color-scheme: light) {
    [data-color-mode=auto][data-light-theme*=light] {
        --csstools-color-scheme--light: initial;
        color-scheme: light;
    }
}
@media (prefers-color-scheme: light) {
    [data-color-mode=auto][data-light-theme*=light] {
        --csstools-color-scheme--light: initial;
        color-scheme: light;
    }
}
@media (prefers-color-scheme: light) {
    [data-color-mode=auto][data-light-theme*=light] {
        --csstools-color-scheme--light: initial;
        color-scheme: light;
    }
}
@media (prefers-color-scheme: light) {
    [data-color-mode=auto][data-light-theme*=light] {
        --csstools-color-scheme--light: initial;
        color-scheme: light;
    }
}
@media (prefers-color-scheme: light) {
    [data-color-mode=auto][data-light-theme*=light] {
        --csstools-color-scheme--light: initial;
        color-scheme: light;
    }
}
@media (prefers-color-scheme: light) {
    [data-color-mode=auto][data-light-theme*=light] {
        --csstools-color-scheme--light: initial;
        color-scheme: light;
    }
}
@media (prefers-color-scheme: light) {
    [data-color-mode=auto][data-light-theme*=light] {
        --csstools-color-scheme--light: initial;
        color-scheme: light;
    }
}
* {
    box-sizing: border-box;
}
* {
    box-sizing: border-box;
}
* {
    box-sizing: border-box;
}
* {
    box-sizing: border-box;
}
* {
    box-sizing: border-box;
}
* {
    box-sizing: border-box;
}
* {
    box-sizing: border-box;
}
* {
    box-sizing: border-box;
}
* {
    box-sizing: border-box;
}
* {
    box-sizing: border-box;
}
* {
    box-sizing: border-box;
}
html {
    font-size: 16px;
    font-family: sans-serif;
    -ms-text-size-adjust: 100%;
    -webkit-text-size-adjust: 100%;
}
* {
    box-sizing: border-box;
}
html[Attributes Style] {
    -webkit-locale: "en";
}
user agent stylesheet
:root {
    view-transition-name: root;
}
user agent stylesheet
html {
    display: block;
}
<style>
--prc-dialog-scrollgutter {
    initial-value: 0;
    inherits: false;
    syntax: "<length>";
}
<style>
--dialog-scrollgutter {
    initial-value: 0;
    inherits: false;
    syntax: "<length>";
Press ctrl i to turn on code suggestions. Press ctrl x to disable code suggestions.
ctrl
i
 to turn on code suggestions. Don't show again NE
