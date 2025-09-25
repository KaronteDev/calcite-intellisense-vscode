# Calcite IntelliSense for HTML and CSS variables.

Injects HTML IntelliSense (completion, hover, documentation) for **Esri Calcite Design System** web components and CSS variables IntelliSense, using Esri’s official custom-data JSON.

## Features

*   Tag and attribute completion for Calcite components
*   Hover documentation (descriptions, attribute value hints)
*   Works in HTML and common web contexts (`.html`, `.ts/.tsx`, `.js/.jsx`, including template strings)
*   CSS Calcite variables completion

## Requirements

*   **VS Code** ≥ 1.93

# Extended Calcite Design System components documentation.

## calcite-accordion

### **Methods**

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding `calcite-accordion-item`s. `calcite-accordion` cannot be nested, however `calcite-accordion-item`s can.

### CSS Properties

*   **\--calcite-accordion-border-color** - Specifies the component's border color.
*   **\--calcite-accordion-background-color** - Specifies the component's background color.
*   **\--calcite-accordion-text-color** - Specifies the component's text color.
*   **\--calcite-accordion-text-color-hover** - Specifies the component's main text color on hover.
*   **\--calcite-accordion-text-color-press** - Specifies the component's main text color when pressed.

---

## calcite-accordion-item

### Events

*   **calciteAccordionItemCollapse** - Fires when the component's content area is collapsed.
*   **calciteAccordionItemExpand** - Fires when the component's content area is expanded.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding custom content, including nested `calcite-accordion-item`s.
*   **actions-end** - A slot for adding `calcite-action`s or content to the end side of the component's header.
*   **actions-start** - A slot for adding `calcite-action`s or content to the start side of the component's header.
*   **content-end** - A slot for adding non-actionable elements after the component's header text.
*   **content-start** - A slot for adding non-actionable elements before the component's header text.

### CSS Properties

*   **\--calcite-accordion-border-color** - Specifies the component's border color.
*   **\--calcite-accordion-background-color** - Specifies the component's background color.
*   **\--calcite-accordion-text-color** - Specifies the component's text color.
*   **\--calcite-accordion-text-color-hover** - Specifies the component's main text color on hover.
*   **\--calcite-accordion-text-color-press** - Specifies the component's main text color when pressed.
*   **\--calcite-accordion-item-background-color** - \[Deprecated\] Use `--calcite-accordion-background-color` . Specifies the component's background color.
*   **\--calcite-accordion-item-border-color** - \[Deprecated\] Use `--calcite-accordion-border-color` . Specifies the component's border color.
*   **\--calcite-accordion-item-content-space** - Specifies the component's padding.
*   **\--calcite-accordion-item-end-icon-color** - Specifies the component's `iconEnd` color. Falls back to `--calcite-accordion-item-icon-color` or current color.
*   **\--calcite-accordion-item-expand-icon-color** - Specifies the component's expand icon color.
*   **\--calcite-accordion-item-header-background-color** - Specifies the component's `heading` background color.
*   **\--calcite-accordion-item-header-background-color-hover** - Specifies the component's `heading` background color when hovered.
*   **\--calcite-accordion-item-header-background-color-press** - Specifies the component's `heading` background color when pressed.
*   **\--calcite-accordion-item-heading-text-color** - Specifies the component's `heading` text color.
*   **\--calcite-accordion-item-icon-color** - \[Deprecated\] Use `--calcite-icon-color` . Specifies the component's default icon color.
*   **\--calcite-accordion-item-start-icon-color** - Specifies the component's `iconStart` color. Falls back to `--calcite-accordion-item-icon-color` or current color.
*   **\--calcite-accordion-item-text-color** - \[Deprecated\] Use `--calcite-accordion-text-color` . Specifies the component's text color.
*   **\--calcite-accordion-item-text-color-hover** - \[Deprecated\] Use `--calcite-accordion-text-color-hover` . Specifies the component's text color on hover.
*   **\--calcite-accordion-item-text-color-press** - \[Deprecated\] Use `--calcite-accordion-text-color-press` . Specifies the component's text color on press.

---

## calcite-action

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding non-interactive content, such as a `calcite-icon`.
*   **tooltip** - \[Deprecated\] Use the `calcite-tooltip` component instead.

### CSS Properties

*   **\--calcite-action-background-color-hover** - Specifies the component's background color when hovered or focused.
*   **\--calcite-action-background-color-press** - Specifies the component's background color when active.
*   **\--calcite-action-background-color-pressed** - \[Deprecated\] Use --calcite-action-background-color-press. Specifies the component's background color when active.
*   **\--calcite-action-background-color** - Specifies the component's background color.
*   **\--calcite-action-corner-radius-end-end** - \[Deprecated\] Use --calcite-action-corner-radius. Specifies the component's corner radius end end.
*   **\--calcite-action-corner-radius-end-start** - \[Deprecated\] Use --calcite-action-corner-radius. Specifies the component's corner radius end start.
*   **\--calcite-action-corner-radius-start-end** - \[Deprecated\] Use --calcite-action-corner-radius. Specifies the component's corner radius start end.
*   **\--calcite-action-corner-radius-start-start** - \[Deprecated\] Use --calcite-action-corner-radius. Specifies the component's corner radius start start.
*   **\--calcite-action-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-action-indicator-color** - Specifies the component's indicator color.
*   **\--calcite-action-text-color-press** - Specifies the component's text color when pressed or hovered.
*   **\--calcite-action-text-color-pressed** - \[Deprecated\] Use --calcite-action-text-color-press. Specifies the component's text color when hovered.
*   **\--calcite-action-text-color** - Specifies the component's text color.

---

## calcite-action-bar

### Events

*   **calciteActionBarCollapse** - Fires when the component's content area is collapsed.
*   **calciteActionBarExpand** - Fires when the component's content area is expanded.
*   **calciteActionBarToggle** - Fires when the `expanded` property is toggled.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

### Slots

*   _default_ - A slot for adding `calcite-action`s that will appear at the top of the component.
*   **bottom-actions** - \[Deprecated\] Use the `"actions-end"` slot instead. A slot for adding `calcite-action`s that will appear at the bottom of the component, above the collapse/expand button.
*   **actions-end** - A slot for adding `calcite-action`s that will appear at the end of the component, prior to the collapse/expand button.
*   **expand-tooltip** - A slot to set the `calcite-tooltip` for the expand toggle.

### CSS Properties

*   **\--calcite-action-bar-background-color** - Specifies the component's background color.
*   **\--calcite-action-bar-corner-radius** - Specifies the component's border radius when `floating` is `true`.
*   **\--calcite-action-bar-expanded-max-width** - When `layout` is `"vertical"`, specifies the component's maximum width.
*   **\--calcite-action-bar-items-space** - Specifies the space between slotted components in the component.
*   **\--calcite-action-bar-shadow** - Specifies the component's shadow when `floating` is `true`.

---

## calcite-action-group

### Events

*   **calciteActionGroupCollapse** - Fires when the component's content area is collapsed.
*   **calciteActionGroupExpand** - Fires when the component's content area is expanded.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

### Slots

*   _default_ - A slot for adding a group of `calcite-action`s.
*   **menu-actions** - A slot for adding an overflow menu with `calcite-action`s inside a `calcite-dropdown`.
*   **menu-tooltip** - A slot for adding a `calcite-tooltip` for the menu.

### CSS Properties

*   **\--calcite-action-background-color** - Specifies the component's background color.
*   **\--calcite-action-group-border-color** - Specifies the component's border color when used in a `calcite-action-bar` or `calcite-action-menu`.
*   **\--calcite-action-group-columns** - When `layout` is `"grid"`, specifies the component's grid-template-columns.
*   **\--calcite-action-group-gap** - When `layout` is `"grid"`, specifies the component's gap.
*   **\--calcite-action-group-padding** - \[Deprecated\] Use `--calcite-action-group-gap`. Specifies the component's padding.

---

## calcite-action-menu

### Events

*   **calciteActionMenuCollapse** - Fires when the component's content area is collapsed.
*   **calciteActionMenuExpand** - Fires when the component's content area is expanded.
*   **calciteActionMenuOpen** - Fires when the `open` property is toggled.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding `calcite-action`s.
*   **trigger** - A slot for adding a `calcite-action` to trigger opening the menu.
*   **tooltip** - A slot for adding a tooltip for the menu.

### CSS Properties

*   **\--calcite-action-menu-items-space** - Specifies the space between actions in the menu.

---

## calcite-action-pad**Deprecated**: Use the `calcite-action-pad` component instead..

### Events

*   **calciteActionPadCollapse** - Fires when the component's content area is collapsed.
*   **calciteActionPadExpand** - Fires when the component's content area is expanded.
*   **calciteActionPadToggle** - Fires when the `expanded` property is toggled.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

### Slots

*   _default_ - A slot for adding `calcite-action`s to the component.
*   **expand-tooltip** - A slot to set the `calcite-tooltip` for the expand toggle.

### CSS Properties

*   **\--calcite-action-pad-corner-radius** - Specifies the component's border radius.
*   **\--calcite-action-pad-expanded-max-width** - When `layout` is `"vertical"`, specifies the component's maximum width when `expanded`.
*   **\--calcite-action-pad-items-space** - Specifies the component's space between slotted components.

---

## calcite-alert

Alerts are meant to provide a way to communicate urgent or important information to users, frequently as a result of an action they took in your app. Alerts are positioned at the bottom of the page. Multiple opened alerts will be added to a queue, allowing users to dismiss them in the order they are provided.

### Events

*   **calciteAlertBeforeClose** - Fires when the component is requested to be closed and before the closing transition begins.
*   **calciteAlertBeforeOpen** - Fires when the component is added to the DOM but not rendered, and before the opening transition begins.
*   **calciteAlertClose** - Fires when the component is closed and animation is complete.
*   **calciteAlertOpen** - Fires when the component is open and animation is complete.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's "close" button, the first focusable item.

`@returns` {Promise}

### Slots

*   **title** - A slot for adding a title to the component.
*   **message** - A slot for adding main text to the component.
*   **link** - A slot for adding a `calcite-action` to take from the component such as: "undo", "try again", "link to page", etc.
*   **actions-end** - A slot for adding `calcite-action`s to the end of the component. It is recommended to use two or fewer actions.

### CSS Properties

*   **\--calcite-alert-width** - Specifies the width of the component.
*   **\--calcite-alert-background-color** - Specifies the component's background color.
*   **\--calcite-alert-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-alert-shadow** - Specifies the component's shadow.
*   **\--calcite-alert-offset-size** - Specifies the component's `placement` offset.

---

## calcite-autocomplete

### Events

*   **calciteAutocompleteBeforeClose** - Fires when the component is requested to be closed and before the closing transition begins.
*   **calciteAutocompleteBeforeOpen** - Fires when the component is added to the DOM but not rendered, and before the opening transition begins.
*   **calciteAutocompleteChange** - Fires each time a new `value` is typed and committed.
*   **calciteAutocompleteClose** - Fires when the component is closed and animation is complete.
*   **calciteAutocompleteOpen** - Fires when the component is open and animation is complete.
*   **calciteAutocompleteTextChange** - Fires each time a new `inputValue` is typed and committed.
*   **calciteAutocompleteTextInput** - Fires each time a new `inputValue` is typed.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `reposition(delayed?: boolean): Promise` - Updates the position of the component.
*   `scrollContentTo(options?: ScrollToOptions): Promise` - Scrolls the component's content to a specified set of coordinates.
*   `selectText(): Promise` - Selects the text of the component's `value` .
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

### Slots

*   _default_ - A slot for adding `calcite-autocomplete-item` elements.
*   **content-bottom** - A slot for adding content below `calcite-autocomplete-item` elements.
*   **content-top** - A slot for adding content above `calcite-autocomplete-item` elements.
*   **label-content** - A slot for rendering content next to the component's `labelText`.

### CSS Properties

*   **\--calcite-autocomplete-background-color** - Specifies the background color of the component.
*   **\--calcite-autocomplete-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-autocomplete-text-color** - Specifies the text color of the component.
*   **\--calcite-autocomplete-input-prefix-size** - Specifies the Input's prefix width, when present.
*   **\--calcite-autocomplete-input-suffix-size** - Specifies the Input's suffix width, when present.
*   **\--calcite-autocomplete-input-background-color** - Specifies the background color of the Input.
*   **\--calcite-autocomplete-input-border-color** - Specifies the border color of the Input.
*   **\--calcite-autocomplete-input-corner-radius** - Specifies the corner radius of the Input.
*   **\--calcite-autocomplete-input-shadow** - Specifies the shadow of the Input.
*   **\--calcite-autocomplete-input-icon-color** - Specifies the icon color of the Input.
*   **\--calcite-autocomplete-input-text-color** - Specifies the text color of the Input.
*   **\--calcite-autocomplete-input-placeholder-text-color** - Specifies the color of placeholder text in the Input.
*   **\--calcite-autocomplete-input-actions-background-color** - Specifies the background color of Input's `clearable` element.
*   **\--calcite-autocomplete-input-actions-background-color-hover** - Specifies the background color of Input's `clearable` element when hovered.
*   **\--calcite-autocomplete-input-actions-background-color-press** - Specifies the background color of Input's `clearable` element when pressed.
*   **\--calcite-autocomplete-input-actions-icon-color** - Specifies the icon color of Input's `clearable` element.
*   **\--calcite-autocomplete-input-actions-icon-color-hover** - Specifies the icon color of Input's `clearable` element when hovered.
*   **\--calcite-autocomplete-input-actions-icon-color-press** - Specifies the icon color of Input's `clearable` element when pressed.
*   **\--calcite-autocomplete-input-loading-background-color** - Specifies the background color of the Input's `loading` element, when present.
*   **\--calcite-autocomplete-input-loading-fill-color** - Specifies the fill color of the Input's `loading` element, when present.
*   **\--calcite-autocomplete-input-prefix-background-color** - Specifies the background color of the Input's prefix, when present.
*   **\--calcite-autocomplete-input-prefix-text-color** - Specifies the text color of the Input's prefix, when present.
*   **\--calcite-autocomplete-input-suffix-background-color** - Specifies the background color of the Input's suffix, when present.
*   **\--calcite-autocomplete-input-suffix-text-color** - Specifies the text color of the Input's suffix, when present.

---

## calcite-autocomplete-item

### Events

*   **calciteAutocompleteItemSelect** - Fires when the item has been selected.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   **content-end** - A slot for adding non-actionable elements after content of the component.
*   **content-start** - A slot for adding non-actionable elements before content of the component.

### CSS Properties

*   **\--calcite-autocomplete-background-color** - Specifies the background color of the component.
*   **\--calcite-autocomplete-description-text-color** - Specifies the text color of the component's description.
*   **\--calcite-autocomplete-heading-text-color** - Specifies the text color of the component's heading.
*   **\--calcite-autocomplete-text-color** - Specifies the text color of the component.

---

## calcite-autocomplete-item-group

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding `calcite-autocomplete-item`s.

### CSS Properties

*   **\--calcite-autocomplete-background-color** - Specifies the background color of the component.
*   **\--calcite-autocomplete-border-color** - Specifies the border color of the component.
*   **\--calcite-autocomplete-text-color** - Specifies the text color of the component.

---

## calcite-avatar

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### CSS Properties

*   **\--calcite-avatar-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-avatar-color** - Specifies the component's icon or initial color.
*   **\--calcite-avatar-background-color** - Specifies the component's background color.

---

## calcite-block

### Events

*   **calciteBlockBeforeClose** - Fires when the component is requested to be closed and before the closing transition begins.
*   **calciteBlockBeforeOpen** - Fires when the component is added to the DOM but not rendered, and before the opening transition begins.
*   **calciteBlockClose** - Fires when the component is closed and animation is complete.
*   **calciteBlockCollapse** - Fires when the component's content area is collapsed.
*   **calciteBlockExpand** - Fires when the component's content area is expanded.
*   **calciteBlockOpen** - Fires when the component is open and animation is complete.
*   **calciteBlockSortHandleBeforeClose** - Fires when the sort handle is requested to be closed and before the closing transition begins.
*   **calciteBlockSortHandleBeforeOpen** - Fires when the sort handle is added to the DOM but not rendered, and before the opening transition begins.
*   **calciteBlockSortHandleClose** - Fires when the sort handle is closed and animation is complete.
*   **calciteBlockSortHandleOpen** - Fires when the sort handle is open and animation is complete.
*   **calciteBlockToggle** - Fires when the component's header is clicked.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first tabbable element.

### Slots

*   _default_ - A slot for adding custom content.
*   **actions-end** - A slot for adding actionable `calcite-action` elements after the content of the component. It is recommended to use two or fewer actions.
*   **icon** - \[Deprecated\] A slot for adding a leading header icon with `calcite-icon`. Use `icon-start` instead.
*   **content-start** - A slot for adding non-actionable elements before content of the component.
*   **control** - \[Deprecated\] A slot for adding a single HTML input element in a header. Use `actions-end` instead.
*   **header-menu-actions** - A slot for adding an overflow menu with `calcite-action`s inside a dropdown menu.

### CSS Properties

*   **\--calcite-block-border-color** - Specifies the component's border color.
*   **\--calcite-block-content-space** - Specifies the space of the component's `default` slot.
*   **\--calcite-block-header-background-color** - Specifies the component's `heading` background color.
*   **\--calcite-block-header-background-color-hover** - Specifies the component's `heading` background color when hovered.
*   **\--calcite-block-header-background-color-press** - Specifies the component's `heading` background color when pressed.
*   **\--calcite-block-heading-text-color** - Specifies the component's `heading` text color.
*   **\--calcite-block-heading-text-color-press** - \[Deprecated\] use `--calcite-block-heading-text-color` instead - When the component is `expanded`, specifies the `heading` text color.
*   **\--calcite-block-padding** - \[Deprecated\] use `--calcite-block-content-space` instead - Specifies the padding of the component's `default` slot.
*   **\--calcite-block-text-color** - \[Deprecated\] Specifies the component's text color.
*   **\--calcite-block-description-text-color** - Specifies the component's `description` text color.
*   **\--calcite-block-icon-color** - Specifies the component's `collapsible` icon, `iconStart` and `iconEnd` color.
*   **\--calcite-block-icon-color-hover** - Specifies the component's `collapsible` icon color when hovered.

---

## calcite-block-group

### Events

*   **calciteBlockGroupDragEnd** - Fires when the component's dragging has ended.
*   **calciteBlockGroupDragStart** - Fires when the component's dragging has started.
*   **calciteBlockGroupMoveHalt** - Fires when a user attempts to move an element using the sort menu and 'canPut' or 'canPull' returns falsy.
*   **calciteBlockGroupOrderChange** - Fires when the component's item order changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

### Slots

*   _default_ - A slot for adding `calcite-block` elements.

---

## calcite-block-section

### Events

*   **calciteBlockSectionCollapse** - Fires when the component's content area is collapsed.
*   **calciteBlockSectionExpand** - Fires when the component's content area is expanded.
*   **calciteBlockSectionToggle** - Fires when the header has been clicked.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first tabbable element.

### Slots

*   _default_ - A slot for adding custom content.

### CSS Properties

*   **\--calcite-block-section-background-color** - Specifies the component's background color.
*   **\--calcite-block-section-border-color** - Specifies the component's border color. When `expanded`, applies to the component's bottom border.
*   **\--calcite-block-section-header-text-color** - Specifies the component's header text color.
*   **\--calcite-block-section-text-color** - Specifies the component's text color.
*   **\--calcite-block-section-text-color-hover** - Specifies the component's text color on hover.
*   **\--calcite-block-section-content-space** - Specifies the padding of the component's content in `default` slot.

---

## calcite-button

Passing a 'href' will render an anchor link, instead of a button. Role will be set to link, or button, depending on this.  
**It is the consumers responsibility to add aria information, rel, target, for links, and any button attributes for form submission**

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding text.

### CSS Properties

*   **\--calcite-button-background-color** - Specifies the component's background color.
*   **\--calcite-button-border-color** - Specifies the component's border color.
*   **\--calcite-button-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-button-icon-color** - Specifies the component's `iconStart` and
*   **\--calcite-button-loader-color** - Specifies the component's loader color.
*   **\--calcite-button-shadow-color** - \[Deprecated\] Use `--calcite-button-shadow`. Specifies the component's box-shadow color.
*   **\--calcite-button-text-color** - Specifies the component's text color.
*   **\--calcite-button-shadow** - Specifies the component's shadow.

---

## calcite-card

### Events

*   **calciteCardSelect** - Fires when the deprecated `selectable` is true, or `selectionMode` set on parent `calcite-card-group` is not `none` and the component is selected.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding content.
*   **title** - \[Deprecated\] use `heading` instead. A slot for adding a heading.
*   **subtitle** - \[Deprecated\] use `description` instead. A slot for adding a description.
*   **thumbnail** - A slot for adding a thumbnail.
*   **heading** - A slot for adding a heading.
*   **description** - A slot for adding a description.
*   **footer-start** - A slot for adding a leading footer.
*   **footer-end** - A slot for adding a trailing footer.

### CSS Properties

*   **\--calcite-card-accent-color-selected** - Specifies the component's accent color when `selected`.
*   **\--calcite-card-background-color** - Specifies the component's background color.
*   **\--calcite-card-border-color** - Specifies the component's border color.
*   **\--calcite-card-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-card-selection-background-color-active** - \[Deprecated\] Use `--calcite-card-selection-background-color-press`. Specifies the component's selection element background color when active.
*   **\--calcite-card-selection-background-color-hover** - Specifies the component's selection element background color when hovered.
*   **\--calcite-card-selection-background-color-press** - Specifies the component's selection element background color when active.
*   **\--calcite-card-selection-background-color-selected** - \[Deprecated\] Use `--calcite-card-background-color`. Specifies the component's selection element icon color when `selected`.
*   **\--calcite-card-selection-background-color** - \[Deprecated\] Use `--calcite-card-background-color`. Specifies the component's selection element background color.
*   **\--calcite-card-selection-color-hover** - Specifies the component's selection element color when hovered or focused.
*   **\--calcite-card-selection-color** - Specifies the component's selection element color.
*   **\--calcite-card-selection-icon-color-hover** - \[Deprecated\] Use `--calcite-card-selection-color-hover`. Specifies the component's selection element icon color when hovered.
*   **\--calcite-card-selection-icon-color-selected** - \[Deprecated\] Use `--calcite-card-accent-color-selected`. Specifies the component's selection element icon color when `selected`.
*   **\--calcite-card-selection-icon-color** - \[Deprecated\] Use `--calcite-card-selection-color`. Specifies the component's selection element icon color.
*   **\--calcite-card-shadow** - Specifies the component's shadow.

---

## calcite-card-group

### Events

*   **calciteCardGroupSelect** - Emits when the component's selection changes and the `selectionMode` is not `none`.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

### Slots

*   _default_ - A slot for adding one or more `calcite-card`s.

### CSS Properties

*   **\--calcite-card-group-gap** - \[Deprecated\] Use `--calcite-card-group-space`. Specifies the gap between slotted elements.
*   **\--calcite-card-group-space** - Specifies the space between slotted elements.

---

## calcite-carousel

### Events

*   **calciteCarouselChange** - Fires when the selected `calcite-carousel-item` changes.
*   **calciteCarouselPause** - Fires when the carousel autoplay state pauses due to a user hovering over the component or focusing on the component or slotted content
*   **calciteCarouselPlay** - Fires when the carousel autoplay is invoked by the user.
*   **calciteCarouselResume** - Fires when the carousel autoplay state resumes due to a user no longer hovering over the component or focusing on the component or slotted content
*   **calciteCarouselStop** - Fires when the carousel autoplay state is stopped by a user.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `play(): Promise` - Play the carousel. If `autoplay` is not enabled (initialized either to `true` or `"paused"` ), these methods will have no effect.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.
*   `stop(): Promise` - Stop the carousel. If `autoplay` is not enabled (initialized either to `true` or `"paused"` ), these methods will have no effect.

### Slots

*   _default_ - A slot for adding `calcite-carousel-item`s.

---

## calcite-carousel-item

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding content.

---

## calcite-checkbox

### Events

*   **calciteCheckboxChange** - Fires when the component's `checked` status changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### CSS Properties

*   **\--calcite-checkbox-size** - Specifies the component's height and width.
*   **\--calcite-checkbox-border-color** - Specifies the component's color.
*   **\--calcite-checkbox-border-color-hover** - Specifies the component's color when hovered.
*   **\--calcite-checkbox-border-color-press** - Specifies the component's color when pressed.
*   **\--calcite-checkbox-icon-color** - Specifies the component's icon color.

---

## calcite-chip

### Events

*   **calciteChipClose** - Fires when the component's close button is selected.
*   **calciteChipSelect** - Fires when the selected state of the component changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding text.
*   **image** - A slot for adding an image.

### CSS Properties

*   **\--calcite-chip-background-color** - Specifies the component's background color.
*   **\--calcite-chip-border-color** - Specifies the component's border color.
*   **\--calcite-chip-close-icon-color** - Specifies the component's close element icon color.
*   **\--calcite-chip-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-chip-icon-color** - Specifies the component's icon color.
*   **\--calcite-chip-select-icon-color-press** - Specifies the component's selection element icon color when active.
*   **\--calcite-chip-select-icon-color-pressed** - \[Deprecated\] Use `--calcite-chip-select-icon-color-press`. Specifies the component's selection element icon color when active.
*   **\--calcite-chip-select-icon-color** - Specifies the component's selection element icon color.
*   **\--calcite-chip-text-color** - Specifies the component's text color.

---

## calcite-chip-group

### Events

*   **calciteChipGroupSelect** - Fires when the component's selection changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

### Slots

*   _default_ - A slot for adding one or more `calcite-chip`s.

---

## calcite-color-picker

### Events

*   **calciteColorPickerChange** - Fires when the color value has changed.
*   **calciteColorPickerInput** - Fires as the color value changes.

Similar to the `calciteColorPickerChange` event with the exception of dragging. When dragging the color field or hue slider thumb, this event fires as the thumb is moved.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

### CSS Properties

*   **\--calcite-color-picker-background-color** - Specifies the component's background color.
*   **\--calcite-color-picker-border-color** - Specifies the component's border color.
*   **\--calcite-color-picker-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-color-picker-shadow** - Specifies the component's shadow.
*   **\--calcite-color-picker-text-color** - Specifies the component's text color.
*   **\--calcite-color-picker-input-background-color** - Specifies the component's input background color.
*   **\--calcite-color-picker-input-border-color** - Specifies the component's input border color.
*   **\--calcite-color-picker-input-text-color** - Specifies the component's input text color.
*   **\--calcite-color-picker-input-prefix-background-color** - When `hexDisabled` is not `true`, specifies the component's input prefix background color.
*   **\--calcite-color-picker-input-prefix-text-color** - When `hexDisabled` is not `true`, specifies the component's input prefix text color.
*   **\--calcite-color-picker-input-suffix-background-color** - When `alphaChannel` is `true`, specifies the component's input suffix background color.
*   **\--calcite-color-picker-input-suffix-text-color** - When `alphaChannel` is `true`, specifies the component's input suffix text color.
*   **\--calcite-color-picker-tab-border-color** - Specifies the component's tab border color.
*   **\--calcite-color-picker-tab-text-color** - Specifies the component's tab text color.
*   **\--calcite-color-picker-tab-accent-color-press** - Specifies the component's tab accent color when selected or active.
*   **\--calcite-color-picker-swatch-corner-radius** - Specifies the component's swatch corner radius.
*   **\--calcite-color-picker-action-text-color-press** - Specifies the component's `savedColors` action text color when pressed.
*   **\--calcite-color-picker-action-text-color-hover** - Specifies the component's `savedColors` action text color when hovered.
*   **\--calcite-color-picker-action-text-color** - Specifies the component's `savedColors` action text color.

---

## calcite-color-picker-hex-input

### Events

*   **calciteColorPickerHexInputChange** - Emitted when the hex value changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

---

## calcite-color-picker-swatch**Deprecated**: Use the `calcite-swatch-group` and `calcite-swatch` components instead..

\--

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

---

## calcite-combobox

### Events

*   **calciteComboboxBeforeClose** - Fires when the component is requested to be closed, and before the closing transition begins.
*   **calciteComboboxBeforeOpen** - Fires when the component is added to the DOM but not rendered, and before the opening transition begins.
*   **calciteComboboxChange** - Fires when the selected item(s) changes.
*   **calciteComboboxChipClose** - Fires when a selected item in the component is closed via its `calcite-chip`.
*   **calciteComboboxClose** - Fires when the component is closed and animation is complete.
*   **calciteComboboxFilterChange** - Fires when text is added to filter the options list.
*   **calciteComboboxOpen** - Fires when the component is open and animation is complete.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `reposition(delayed?: boolean): Promise` - Updates the position of the component.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding `calcite-combobox-item`s.
*   **label-content** - A slot for rendering content next to the component's `labelText`.

### CSS Properties

*   **\--calcite-combobox-divider-color** - Specifies the component's divider color.
*   **\--calcite-combobox-icon-color** - Specifies the component's icon color.
*   **\--calcite-combobox-icon-color-hover** - Specifies the component's icon color when hovered.
*   **\--calcite-combobox-background-color** - Specifies the background color of the component's listbox.
*   **\--calcite-combobox-input-border-color** - Specifies the border color of the component's input.
*   **\--calcite-combobox-input-background-color** - Specifies the background color of the component's input.
*   **\--calcite-combobox-input-height** - Specifies the height of the component's input.
*   **\--calcite-combobox-input-text-color** - When `selectionDisplay` is `"single"`, specifies the text color of the component's input.

---

## calcite-combobox-item

### Events

*   **calciteComboboxItemChange** - Fires whenever the component is selected or unselected.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding nested `calcite-combobox-item`s.
*   **content-end** - A slot for adding non-actionable elements after the component's content.
*   **content-start** - A slot for adding non-actionable elements before the component's content.

### CSS Properties

*   **\--calcite-combobox-item-border-color** - \[Deprecated\] Specifies the component's border color.
*   **\--calcite-combobox-text-color** - Specifies the component's text and `icon` color.
*   **\--calcite-combobox-text-color-hover** - Specifies the component's text and `icon` color when hovered.
*   **\--calcite-combobox-item-background-color-active** - Specifies the component's background color when active.
*   **\--calcite-combobox-item-background-color-hover** - Specifies the component's background color when hovered.
*   **\--calcite-combobox-item-shadow** - Specifies the component's shadow.
*   **\--calcite-combobox-selected-icon-color** - Specifies the component's selected indicator icon color.
*   **\--calcite-combobox-description-text-color** - Specifies the component's `description` and `shortHeading` text color.
*   **\--calcite-combobox-description-text-color-press** - Specifies the component's `description` and `shortHeading` text color when hovered.
*   **\--calcite-combobox-heading-text-color** - Specifies the component's `heading` text color.

---

## calcite-combobox-item-group

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding `calcite-combobox-item`s.

### CSS Properties

*   **\--calcite-combobox-item-group-text-color** - Specifies the text color of the component.
*   **\--calcite-combobox-item-group-border-color** - Specifies the border color of the component.

---

## calcite-date-picker

### Events

*   **calciteDatePickerChange** - Fires when a user changes the component's date. For `range` events, use `calciteDatePickerRangeChange`.
*   **calciteDatePickerRangeChange** - Fires when a user changes the component's date `range`. For components without `range` use `calciteDatePickerChange`.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

### CSS Properties

*   **\--calcite-date-picker-border-color** - Specifies the component's border color.
*   **\--calcite-date-picker-corner-radius** - Specifies the component's border radius.
*   **\--calcite-date-picker-range-calendar-divider-color** - Specifies the divider color between calendar's when `range="true"`.
*   **\--calcite-date-picker-week-header-text-color** - Specifies the week header text color.
*   **\--calcite-date-picker-header-action-background-color** - Specifies the background color of header action's of the component.
*   **\--calcite-date-picker-header-action-background-color-hover** - Specifies the background color of header action's of the component when hovered.
*   **\--calcite-date-picker-header-action-background-color-press** - Specifies the background color of header action's of the component when pressed.
*   **\--calcite-date-picker-header-action-text-color** - Specifies the text color of header action's of the component.
*   **\--calcite-date-picker-header-action-text-color-press** - Specifies the text color of header action's of the component when pressed.
*   **\--calcite-date-picker-year-text-color** - Specifies the text color of year & suffix of the component.
*   **\--calcite-date-picker-month-select-font-size** - Specifies the font size of month select of the component.
*   **\--calcite-date-picker-month-select-text-color** - Specifies the text color of month select of the component.
*   **\--calcite-date-picker-month-select-icon-color** - Specifies the icon color of month select of the component.
*   **\--calcite-date-picker-month-select-icon-color-hover** - Specifies the icon color of month select of the component when hovered.
*   **\--calcite-date-picker-day-background-color** - Specifies the background color of day of the component.
*   **\--calcite-date-picker-day-background-color-hover** - Specifies the background color of day of the component when hovered.
*   **\--calcite-date-picker-day-text-color** - Specifies the text color of day of the component.
*   **\--calcite-date-picker-day-text-color-hover** - Specifies the text color of day of the component when hovered.
*   **\--calcite-date-picker-current-day-text-color** - Specifies the text color of current day of the component.
*   **\--calcite-date-picker-day-background-color-selected** - Specifies the background color of selected day of the component.
*   **\--calcite-date-picker-day-text-color-selected** - Specifies the text color of selected day of the component.
*   **\--calcite-date-picker-day-range-text-color** - Specifies the text color of select day range of the component.
*   **\--calcite-date-picker-day-range-background-color** - Specifies the background color of select day range of the component.
*   **\--calcite-date-picker-day-outside-range-background-color-hover** - Specifies the background color of day's outside current range when hovered.
*   **\--calcite-date-picker-day-outside-range-text-color-hover** - Specifies the text color of day's outside current range when hovered.

---

## calcite-date-picker-day

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

---

## calcite-date-picker-month

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

---

## calcite-date-picker-month-header

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

---

## calcite-dialog

### Events

*   **calciteDialogBeforeClose** - Fires when the component is requested to be closed and before the closing transition begins.
*   **calciteDialogBeforeOpen** - Fires when the component is added to the DOM but not rendered, and before the opening transition begins.
*   **calciteDialogClose** - Fires when the component is closed and animation is complete.
*   **calciteDialogOpen** - Fires when the component is open and animation is complete.
*   **calciteDialogScroll** - Fires when the content is scrolled.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `scrollContentTo(options?: ScrollToOptions): Promise` - Scrolls the component's content to a specified set of coordinates.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's "close" button (the first focusable item).
*   `updateFocusTrapElements(extraContainers?: FocusTrapOptions\["extraContainers"\]): Promise` - Updates the element(s) that are included in the focus-trap of the component.

### Slots

*   _default_ - A slot for adding content.
*   **content** - \[Deprecated\] Use `custom-content` slot instead.
*   **custom-content** - A slot for displaying custom content. Will prevent the rendering of any default Dialog UI, except for `box-shadow` and `corner-radius` .
*   **action-bar** - A slot for adding a `calcite-action-bar` to the component.
*   **alerts** - A slot for adding `calcite-alert` s to the component.
*   **content-bottom** - A slot for adding content below the unnamed (default) slot and - if populated - the `footer` slot.
*   **content-top** - A slot for adding content above the unnamed (default) slot and - if populated - below the `action-bar` slot.
*   **header-actions-start** - A slot for adding actions or content to the starting side of the component's header.
*   **header-actions-end** - A slot for adding actions or content to the ending side of the component's header.
*   **header-content** - A slot for adding custom content to the component's header.
*   **header-menu-actions** - A slot for adding an overflow menu with actions inside a `calcite-dropdown` .
*   **fab** - A slot for adding a `calcite-fab` (floating action button) to perform an action.
*   **footer** - A slot for adding custom content to the component's footer. Should not be used with the `"footer-start"` or `"footer-end"` slots.
*   **footer-end** - A slot for adding a trailing footer custom content. Should not be used with the `"footer"` slot.
*   **footer-start** - A slot for adding a leading footer custom content. Should not be used with the `"footer"` slot.

### CSS Properties

*   **\--calcite-dialog-scrim-background-color** - Specifies the background color of the component's scrim.
*   **\--calcite-dialog-size-x** - Specifies the width of the component, using `px`, `em`, `rem`, `vw`, or `%`. Does not exceed the viewport's width - applies when `placement="cover"` is set.
*   **\--calcite-dialog-min-size-x** - Specifies the minimum width of the component, using `px`, `em`, `rem`, `vw`, or `%`.
*   **\--calcite-dialog-max-size-x** - Specifies the maximum width of the component, using `px`, `em`, `rem`, `vw`, or `%`.
*   **\--calcite-dialog-size-y** - Specifies the height of the component, using `px`, `em`, `rem`, `vh`, or `%`. Does not exceed the viewport's height - applies when `placement="cover"` is set.
*   **\--calcite-dialog-min-size-y** - Specifies the minimum height of the component, using `px`, `em`, `rem`, `vh`, or `%`.
*   **\--calcite-dialog-max-size-y** - Specifies the maximum height of the component, using `px`, `em`, `rem`, `vh`, or `%`.
*   **\--calcite-dialog-content-space** - Specifies the padding of the component's content.
*   **\--calcite-dialog-footer-space** - Specifies the padding of the component's footer.
*   **\--calcite-dialog-border-color** - Specifies the component's border color.
*   **\--calcite-dialog-offset-x** - Specifies the horizontal offset of the component.
*   **\--calcite-dialog-offset-y** - Specifies the vertical offset of the component.
*   **\--calcite-dialog-background-color** - Specifies the background color of the component.
*   **\--calcite-dialog-icon-color** - Specifies the color of the component's icon.
*   **\--calcite-dialog-accent-color** - Specifies the component's accent color when `kind` is specified.
*   **\--calcite-dialog-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-dialog-heading-text-color** - Specifies the text color of the component's `heading`.
*   **\--calcite-dialog-description-text-color** - Specifies the text color of the component's `description`.
*   **\--calcite-dialog-border-color** - Specifies the component's border color.
*   **\--calcite-dialog-header-background-color** - Specifies the background color of the component's header.
*   **\--calcite-dialog-header-action-background-color** - Specifies the background color of Panel's `closable`, `collapsible`, and elements slotted in `header-menu-actions`.
*   **\--calcite-dialog-header-action-background-color-hover** - Specifies the background color of Panel's `closable`, `collapsible`, and elements slotted in `header-menu-actions` when hovered.
*   **\--calcite-dialog-header-action-background-color-press** - Specifies the background color of Panel's `closable`, `collapsible`, and elements slotted in `header-menu-actions` when pressed.
*   **\--calcite-dialog-header-action-text-color** - Specifies the text color of Panel's `closable`, `collapsible`, and elements slotted in `header-menu-actions`.
*   **\--calcite-dialog-header-action-text-color-press** - Specifies the text color of Panel's `closable`, `collapsible`, and elements slotted in `header-menu-actions` when pressed or hovered.
*   **\--calcite-dialog-footer-background-color** - Specifies the background color of the component's footer.
*   **\--calcite-dialog-space** - Specifies the padding of the component's `"unnamed (default)"` slot.
*   **\--calcite-dialog-header-content-space** - Specifies the padding of the `"header-content"` slot.
*   **\--calcite-dialog-footer-space** - Specifies the padding of the component's footer.
*   **\--calcite-dialog-action-menu-border-color** - Specifies the border color of the component's internally rendered `calcite-popover`, which is rendered within a `calcite-action` menu when slotted `calcite-action`s are present in the `header-actions-end` slot. Applies to any slotted `calcite-popover`s.

---

## calcite-dropdown

### Events

*   **calciteDropdownBeforeClose** - Fires when the component is requested to be closed and before the closing transition begins.
*   **calciteDropdownBeforeOpen** - Fires when the component is added to the DOM but not rendered, and before the opening transition begins.
*   **calciteDropdownClose** - Fires when the component is closed and animation is complete.
*   **calciteDropdownOpen** - Fires when the component is open and animation is complete.
*   **calciteDropdownSelect** - Fires when a `calcite-dropdown-item`'s selection changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `reposition(delayed?: boolean): Promise` - Updates the position of the component.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

### Slots

*   _default_ - A slot for adding `calcite-dropdown-group` elements. Every `calcite-dropdown-item` must have a parent `calcite-dropdown-group`, even if the `groupTitle` property is not set.
*   **trigger** - A slot for the element that triggers the `calcite-dropdown`.

### CSS Properties

*   **\--calcite-dropdown-width** - Specifies the width of the component's wrapper.
*   **\--calcite-dropdown-background-color** - Specifies the component's background color.

---

## calcite-dropdown-group

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding `calcite-dropdown-item`s.

### CSS Properties

*   **\--calcite-dropdown-group-border-color** - Specifies the `calcite-dropdown`'s border color.
*   **\--calcite-dropdown-group-title-text-color** - Specifies the component's `groupTitle` color.

---

## calcite-dropdown-item

### Events

*   **calciteDropdownItemSelect** - Fires when the component is selected.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding text.

### CSS Properties

*   **\--calcite-dropdown-item-background-color-hover** - Specifies the item's background color when hovered.
*   **\--calcite-dropdown-item-background-color-press** - Specifies the item's background color when selected or active.
*   **\--calcite-dropdown-item-icon-color-hover** - \[Deprecated\] Specifies the item's icon selection color when hovered.
*   **\--calcite-dropdown-item-icon-color-press** - Specifies the item's icon selection color when selected or active.
*   **\--calcite-dropdown-item-text-color-press** - Specifies the item's text when selected or active.
*   **\--calcite-dropdown-item-text-color** - Specifies the item's text color.

---

## calcite-fab

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### CSS Properties

*   **\--calcite-fab-background-color** - Specifies the component's background color.
*   **\--calcite-fab-border-color** - Specifies the component's border color.
*   **\--calcite-fab-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-fab-text-color** - Specifies the component's text color.
*   **\--calcite-fab-loader-color** - Specifies the component's loader color.
*   **\--calcite-fab-shadow** - Specifies the component's shadow.

---

## calcite-filter

### Events

*   **calciteFilterChange** - Fires when the filter text changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `filter(value?: string): Promise` - Performs a filter on the component.

This method can be useful because filtering is delayed and asynchronous.

*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### CSS Properties

*   **\--calcite-filter-content-space** - Specifies the padding of the component's content.
*   **\--calcite-filter-input-background-color** - Specifies the input's background color.
*   **\--calcite-filter-input-border-color** - Specifies the input's border color.
*   **\--calcite-filter-input-corner-radius** - Specifies the input's corner radius.
*   **\--calcite-filter-input-shadow** - Specifies the shadow around the input.
*   **\--calcite-filter-input-icon-color** - Specifies the input's icon color.
*   **\--calcite-filter-input-text-color** - Specifies the input's text color.
*   **\--calcite-filter-input-placeholder-text-color** - Specifies the input's placeholder text color.
*   **\--calcite-filter-input-actions-background-color** - Specifies the background color of the input's `clearable` element.
*   **\--calcite-filter-input-actions-background-color-hover** - Specifies the background color of the input's `clearable` element when hovered.
*   **\--calcite-filter-input-actions-background-color-press** - Specifies the background color of the input's `clearable` element when pressed.
*   **\--calcite-filter-input-actions-icon-color** - Specifies the icon color of the input's `clearable` element.
*   **\--calcite-filter-input-actions-icon-color-hover** - Specifies the icon color of the input's `clearable` element when hovered.
*   **\--calcite-filter-input-actions-icon-color-press** - Specifies the icon color of the input's `clearable` element when pressed.

---

## calcite-flow

### Methods

*   \`back(): Promise\<FlowItem\["el"\]

---

## calcite-flow-item

### Events

*   **calciteFlowItemBack** - Fires when the back button is clicked.
*   **calciteFlowItemClose** - Fires when the close button is clicked.
*   **calciteFlowItemCollapse** - Fires when the component's content area is collapsed.
*   **calciteFlowItemExpand** - Fires when the component's content area is expanded.
*   **calciteFlowItemScroll** - Fires when the content is scrolled.
*   **calciteFlowItemToggle** - Fires when the collapse button is clicked.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `scrollContentTo(options?: ScrollToOptions): Promise` - Scrolls the component's content to a specified set of coordinates.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding custom content.
*   **action-bar** - A slot for adding a `calcite-action-bar` to the component.
*   **alerts** - A slot for adding `calcite-alert` s to the component.
*   **content-top** - A slot for adding content above the unnamed (default) slot and below the action-bar slot (if populated).
*   **content-bottom** - A slot for adding content below the unnamed (default) slot and above the footer slot (if populated)
*   **header-actions-start** - A slot for adding `calcite-action` s or content to the start side of the component's header.
*   **header-actions-end** - A slot for adding `calcite-action` s or content to the end side of the component's header.
*   **header-content** - A slot for adding custom content to the component's header.
*   **header-menu-actions** - A slot for adding an overflow menu with `calcite-action` s inside a `calcite-dropdown` .
*   **fab** - A slot for adding a `calcite-fab` (floating action button) to perform an action.
*   **footer** - A slot for adding custom content to the component's footer. Should not be used with the `"footer-start"` or `"footer-end"` slots.
*   **footer-actions** - \[Deprecated\] Use the `"footer"` slot instead. A slot for adding `calcite-button` s to the component's footer.
*   **footer-end** - A slot for adding a trailing footer custom content. Should not be used with the `"footer"` slot.
*   **footer-start** - A slot for adding a leading footer custom content. Should not be used with the `"footer"` slot.

### CSS Properties

*   **\--calcite-flow-item-footer-padding** - \[Deprecated\] Use `--calcite-flow-footer-space` instead. Specifies the padding of the component's footer.
*   **\--calcite-flow-item-header-border-block-end** - \[Deprecated\] Use `--calcite-flow-border-color` instead. Specifies the component header's block end border.
*   **\--calcite-flow-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-flow-heading-text-color** - Specifies the text color of the component's `heading`.
*   **\--calcite-flow-icon-color** - Specifies the color of the component's icon.
*   **\--calcite-flow-description-text-color** - Specifies the text color of the component's `description`.
*   **\--calcite-flow-border-color** - Specifies the component's border color.
*   **\--calcite-flow-background-color** - Specifies the component's background color.
*   **\--calcite-flow-header-background-color** - Specifies the background color of the component's header.
*   **\--calcite-flow-footer-background-color** - Specifies the background color of the component's footer.
*   **\--calcite-flow-space** - Specifies the padding of the component's `"unnamed (default)"` slot.
*   **\--calcite-flow-header-content-space** - Specifies the padding of the `"header-content"` slot.
*   **\--calcite-flow-footer-space** - Specifies the padding of the component's footer.
*   **\--calcite-action-background-color** - Specifies the background color of the component's `closable`, `collapsible`, and `back` `calcite-action`s. Applies to any slotted `calcite-action`s.
*   **\--calcite-action-background-color-hover** - Specifies the background color of the component's `closable`, `collapsible`, and `back` `calcite-action`s when hovered. Applies to any slotted `calcite-action`s.
*   **\--calcite-action-background-color-pressed** - Specifies the background color of the component's `closable`, `collapsible`, and `back` `calcite-action`s when pressed. Applies to any slotted `calcite-action`s.
*   **\--calcite-action-text-color-hover** - Specifies the text and icon color of the component's `closable`, `collapsible`, and `back` `calcite-action`s when hovered. Applies to any slotted `calcite-action`s.
*   **\--calcite-action-text-color-pressed** - Specifies the text and icon color of the component's `closable`, `collapsible`, and `back` `calcite-action`s when pressed. Applies to any slotted `calcite-action`s.
*   **\--calcite-popover-border-color** - Specifies the border color of the component's internally rendered `calcite-popover`, which is rendered within a `calcite-action` menu when slotted `calcite-action`s are present in the `header-actions-end` slot. Applies to any slotted `calcite-popover`s.
*   **\--calcite-flow-header-action-background-color-hover** - Specifies the background color of the component's `calcite-action` items in the flow item header when hovered.
*   **\--calcite-flow-header-action-background-color-press** - Specifies the background color of the component's `calcite-action` items in the flow item header when pressed.
*   **\--calcite-flow-header-action-background-color** - Specifies the background color of the component's `calcite-action` items in the flow item header.
*   **\--calcite-flow-header-action-indicator-color** - Specifies the color of the component's `calcite-action` items' indicator in the flow item header.
*   **\--calcite-flow-header-action-text-color-press** - Specifies the text color of the component's `calcite-action` items in the flow item header when pressed.
*   **\--calcite-flow-header-action-text-color** - Specifies the text color of the component's `calcite-action` items in the flow item header.

---

## calcite-graph

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### CSS Properties

*   **\--calcite-graph-highlight-fill-color** - Specifies the fill color of the `highlight` element, when present.

---

## calcite-handle**Deprecated**: Use the `calcite-sort-handle` component instead..

\--

### Events

*   **calciteHandleChange** - Fires whenever the component is selected or unselected.
*   **calciteHandleNudge** - Fires when the handle is selected and the up or down arrow key is pressed.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### CSS Properties

*   **\--calcite-handle-background-color** - Specifies the component's background color.
*   **\--calcite-handle-background-color-hover** - Specifies the component's background color on hover.
*   **\--calcite-handle-background-color-selected** - Specifies the component's background color when selected.
*   **\--calcite-handle-icon-color** - Specifies the component's icon color.
*   **\--calcite-handle-icon-color-hover** - Specifies the component's icon color on hover.
*   **\--calcite-handle-icon-color-selected** - Specifies the component's icon color when selected.

---

## calcite-icon

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### CSS Properties

*   **\--calcite-ui-icon-color** - \[Deprecated\] Use `--calcite-icon-color`. Specifies the component's color. Defaults to current color.
*   **\--calcite-icon-color** - Specifies the component's color. Defaults to current color.

---

## calcite-inline-editable

### Events

*   **calciteInlineEditableEditCancel** - Emits when the component's "cancel editing" button is pressed.
*   **calciteInlineEditableEditConfirm** - Emits when the component's "confirm edits" button is pressed.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding a `calcite-input`.

### CSS Properties

*   **\--calcite-inline-editable-background-color-hover** - Specifies the component's background color when hovered.
*   **\--calcite-inline-editable-background-color** - Specifies the component's background color.
*   **\--calcite-inline-editable-button-background-color** - Specifies the button element's background color when appearance="solid" or appearance="outline-fill".
*   **\--calcite-inline-editable-button-corner-radius** - Specifies the button element's corner radius.
*   **\--calcite-inline-editable-button-loader-color** - Specifies the button element's loader color.
*   **\--calcite-inline-editable-button-shadow-color** - Specifies the button element's box-shadow color.
*   **\--calcite-inline-editable-button-text-color** - Specifies the button element's text color.

---

## calcite-input

### Events

*   **calciteInputChange** - Fires each time a new `value` is typed and committed.
*   **calciteInputInput** - Fires each time a new `value` is typed.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `selectText(): Promise` - Selects the text of the component's `value` .
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   **action** - A slot for positioning a `calcite-button` next to the component.
*   **label-content** - A slot for rendering content next to the component's `labelText`.

### CSS Properties

*   **\--calcite-input-prefix-size** - Specifies the component's prefix width, when present.
*   **\--calcite-input-suffix-size** - Specifies the component's suffix width, when present.
*   **\--calcite-input-background-color** - Specifies the component's background color.
*   **\--calcite-input-border-color** - Specifies the component's border color.
*   **\--calcite-input-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-input-shadow** - Specifies the shadow around the component.
*   **\--calcite-input-icon-color** - Specifies the component's icon color.
*   **\--calcite-input-text-color** - Specifies the component's text color.
*   **\--calcite-input-placeholder-text-color** - Specifies the component's placeholder text color.
*   **\--calcite-input-actions-background-color** - Specifies the background color of the component's `clearable` and `number-button-type` elements.
*   **\--calcite-input-actions-background-color-hover** - Specifies the background color of the component's `clearable` and `number-button-type` elements when hovered.
*   **\--calcite-input-actions-background-color-press** - Specifies the background color of the component's `clearable` and `number-button-type` elements when pressed.
*   **\--calcite-input-actions-icon-color** - Specifies the icon color of the component's `clearable` and `number-button-type` elements.
*   **\--calcite-input-actions-icon-color-hover** - Specifies the icon color of the component's `clearable` and `number-button-type` elements when hovered.
*   **\--calcite-input-actions-icon-color-press** - Specifies the icon color of the component's `clearable` and `number-button-type` elements when pressed.
*   **\--calcite-input-loading-background-color** - Specifies the background color of the `loading` element, when present.
*   **\--calcite-input-loading-fill-color** - Specifies the fill color of the `loading` element, when present.
*   **\--calcite-input-prefix-background-color** - Specifies the component's prefix background color, when present.
*   **\--calcite-input-prefix-text-color** - Specifies the component's prefix text color, when present.
*   **\--calcite-input-suffix-background-color** - Specifies the component's suffix background color, when present.
*   **\--calcite-input-suffix-text-color** - Specifies the component's suffix text color, when present.

---

## calcite-input-date-picker

### Events

*   **calciteInputDatePickerBeforeClose** - Fires when the component is requested to be closed and before the closing transition begins.
*   **calciteInputDatePickerBeforeOpen** - Fires when the component is added to the DOM but not rendered, and before the opening transition begins.
*   **calciteInputDatePickerChange** - Fires when the component's `value` changes.
*   **calciteInputDatePickerClose** - Fires when the component is closed and animation is complete.
*   **calciteInputDatePickerOpen** - Fires when the component is open and animation is complete.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `reposition(delayed?: boolean): Promise` - Updates the position of the component.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   **label-content** - A slot for rendering content next to the component's `labelText`.

### CSS Properties

*   **\--calcite-input-date-picker-border-color** - Specifies the component's input border color.
*   **\--calcite-input-date-picker-divider-color** - Specifies the component's divider color between two inputs when in range mode.
*   **\--calcite-input-date-picker-shadow** - Specifies the component's input shadow.
*   **\--calcite-input-date-picker-calendar-shadow** - the component's calendar shadow.
*   **\--calcite-input-date-picker-icon-color** - Specifies the component's in-field input icon color.
*   **\--calcite-input-date-picker-icon-color-hover** - Specifies the component's in-field input icon color on hover.
*   **\--calcite-input-date-picker-actions-icon-color** - Specifies the component's actions icon color.
*   **\--calcite-input-date-picker-actions-icon-color-hover** - Specifies the component's actions icon color on hover.
*   **\--calcite-input-date-picker-calendar-icon-color** - Specifies the component's calendar icon color.
*   **\--calcite-input-date-picker-calendar-icon-color-hover** - Specifies the component's calendar icon color.
*   **\--calcite-input-date-picker-background-color** - Specifies the component's input background color.
*   **\--calcite-input-date-picker-calendar-actions-background-color** - Specifies the background color of actions of the calendar.
*   **\--calcite-input-date-picker-calendar-actions-background-color-hover** - Specifies the background color of actions of the calendar when hovered.
*   **\--calcite-input-date-picker-calendar-actions-background-color-press** - Specifies the background color of actions of the calendar when pressed.
*   **\--calcite-input-date-picker-calendar-selected-background-color** - Specifies the background color of selected day and day range of the calendar.
*   **\--calcite-input-date-picker-calendar-day-background-color** - Specifies the background color of day of the calendar.
*   **\--calcite-input-date-picker-calendar-day-background-color-hover** - Specifies the background color of day of the calendar when hovered.
*   **\--calcite-input-date-picker-calendar-day-outside-range-background-color-hover** - Specifies the background color of day's outside current range of the component's date-picker when hovered.
*   **\--calcite-input-date-picker-corner-radius** - Specifies the component's input corner radius.
*   **\--calcite-input-date-picker-calendar-corner-radius** - Specifies the component's calendar corner radius.
*   **\--calcite-input-date-picker-text-color** - Specifies the component's input text color.
*   **\--calcite-input-date-picker-placeholder-text-color** - Specifies the component's input placeholder text color.
*   **\--calcite-input-date-picker-calendar-actions-text-color** - Specifies the text color of the component's calendar actions.
*   **\--calcite-input-date-picker-calendar-actions-text-color-press** - Specifies the text color of the component's calendar actions when pressed.
*   **\--calcite-input-date-picker-calendar-text-color** - Specifies the text color of the component's calendar week, year & suffix.
*   **\--calcite-input-date-picker-calendar-month-select-text-color** - Specifies the text color of month select of the component's date-picker.
*   **\--calcite-input-date-picker-calendar-day-text-color** - Specifies the text color of day of the component's date-picker.
*   **\--calcite-input-date-picker-calendar-day-text-color-hover** - Specifies the text color of day of the component's date-picker when hovered.
*   **\--calcite-input-date-picker-calendar-day-current-text-color** - Specifies the text color of current day of the component's date-picker.
*   **\--calcite-input-date-picker-calendar-day-text-color-selected** - Specifies the text color of selected day of the component's date-picker.
*   **\--calcite-input-date-picker-calendar-day-range-text-color** - Specifies the text color of select day range of the component's date-picker.
*   **\--calcite-input-date-picker-calendar-day-outside-range-text-color-hover** - Specifies the text color of day's outside current range of the component's date-picker when hovered.
*   **\--calcite-input-date-picker-calendar-border-color** - Specifies the component's calendar border color.
*   **\--calcite-input-date-picker-calendar-range-divider-color** - Specifies the divider color between the component's date-picker

---

## calcite-input-message

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding text.

### CSS Properties

*   **\--calcite-input-message-spacing-value** - \[Deprecated\] Use `--calcite-input-message-spacing`. Specifies the margin spacing at the top of the component.
*   **\--calcite-input-message-spacing** - Specifies the margin spacing at the top of the component.
*   **\--calcite-input-message-icon-color** - Specifies the component's icon color.

---

## calcite-input-number

### Events

*   **calciteInputNumberChange** - Fires each time a new value is typed and committed.
*   **calciteInputNumberInput** - Fires each time a new value is typed.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `selectText(): Promise` - Selects the text of the component's `value` .
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   **action** - A slot for positioning a `calcite-action` or other interactive content.
*   **label-content** - A slot for rendering content next to the component's `labelText`.

### CSS Properties

*   **\--calcite-input-actions-background-color** - Specifies the background color of the component's `clearable` and `number-button-type` elements.
*   **\--calcite-input-actions-background-color-hover** - Specifies the background color of the component's `clearable` and `number-button-type` elements when hovered.
*   **\--calcite-input-actions-background-color-press** - Specifies the background color of the component's `clearable` and `number-button-type` elements when pressed.
*   **\--calcite-input-actions-icon-color** - Specifies the icon color of the component's `clearable` and `number-button-type` elements.
*   **\--calcite-input-actions-icon-color-hover** - Specifies the icon color of the component's `clearable` and `number-button-type` elements when hovered.
*   **\--calcite-input-actions-icon-color-press** - Specifies the icon color of the component's `clearable` and `number-button-type` elements when pressed.
*   **\--calcite-input-loading-background-color** - Specifies the background color of the `loading` element.
*   **\--calcite-input-loading-fill-color** - Specifies the fill color of the `loading` element.
*   **\--calcite-input-number-background-color** - Specifies the background color of the component.
*   **\--calcite-input-number-border-color** - Specifies the border color of the component.
*   **\--calcite-input-number-corner-radius** - Specifies the border radius of the component.
*   **\--calcite-input-number-icon-color** - Specifies the component's icon color.
*   **\--calcite-input-number-height** - Specifies the height of the component.
*   **\--calcite-input-number-placeholder-text-color** - Specifies the text color of the placeholder in the component.
*   **\--calcite-input-number-text-color** - Specifies the text color of the component.
*   **\--calcite-input-number-text-color-focus** - Specifies the text color of the component when focused.
*   **\--calcite-input-prefix-background-color** - Specifies the background color of the prefix element.
*   **\--calcite-input-prefix-size** - Specifies the width of the prefix element.
*   **\--calcite-input-prefix-text-color** - Specifies the text color of the prefix element.
*   **\--calcite-input-suffix-background-color** - Specifies the background color of the suffix element.
*   **\--calcite-input-suffix-size** - Specifies the width of the suffix element.
*   **\--calcite-input-suffix-text-color** - Specifies the text color of the suffix element.

---

## calcite-input-text

### Events

*   **calciteInputTextChange** - Fires each time a new value is typed and committed.
*   **calciteInputTextInput** - Fires each time a new value is typed.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `selectText(): Promise` - Selects the text of the component's `value` .
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   **action** - A slot for positioning a button next to the component.
*   **label-content** - A slot for rendering content next to the component's `labelText`.

### CSS Properties

*   **\--calcite-input-action-background-color** - Specifies the background color of the component's `clearable` element.
*   **\--calcite-input-action-background-color-hover** - Specifies the background color of the component's `clearable` element when hovered.
*   **\--calcite-input-action-background-color-press** - Specifies the background color of the component's `clearable` element when pressed.
*   **\--calcite-input-action-icon-color** - Specifies the icon color of the component's `clearable` & icon elements.
*   **\--calcite-input-action-icon-color-hover** - Specifies the icon color of the component's `clearable` & icon elements when hovered.
*   **\--calcite-input-action-icon-color-press** - Specifies the icon color of the component's `clearable` & icon elements when pressed.
*   **\--calcite-input-loading-background-color** - Specifies the background color of the `loading` element.
*   **\--calcite-input-loading-fill-color** - Specifies the fill color of the `loading` element.
*   **\--calcite-input-prefix-background-color** - When `prefixText` is provided, specifies the background color of the component's prefix element.
*   **\--calcite-input-prefix-size-x** - When `prefixText` is provided, specifies the width of the component's prefix element.
*   **\--calcite-input-prefix-text-color** - When `prefixText` is provided, specifies the text color of the component's prefix element.
*   **\--calcite-input-suffix-background-color** - When `suffixText` is provided, specifies the background color of the component's suffix element.
*   **\--calcite-input-suffix-size-x** - When `suffixText` is provided, specifies the width of the component's suffix element.
*   **\--calcite-input-suffix-text-color** - When `suffixText` is provided, specifies the color of the component's suffix element.
*   **\--calcite-input-text-background-color** - Specifies the component's background color.
*   **\--calcite-input-text-border-color** - Specifies the component's border color.
*   **\--calcite-input-text-corner-radius** - Specifies the component's border radius.
*   **\--calcite-input-text-icon-color** - Specifies the component's icon color.
*   **\--calcite-input-text-placeholder-text-color** - Specifies the component's `placeholder` text color.
*   **\--calcite-input-text-text-color** - Specifies the component's text color.
*   **\--calcite-input-text-text-color-focus** - Specifies the component's text color when focused.

---

## calcite-input-time-picker

### Events

*   **calciteInputTimePickerBeforeClose** - Fires when the component is requested to be closed and before the closing transition begins.
*   **calciteInputTimePickerBeforeOpen** - Fires when the component is added to the DOM but not rendered, and before the opening transition begins.
*   **calciteInputTimePickerChange** - Fires when the component's `value` is modified by the user.
*   **calciteInputTimePickerClose** - Fires when the component is closed and animation is complete.
*   **calciteInputTimePickerOpen** - Fires when the component is open and animation is complete.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `reposition(delayed?: boolean): Promise` - Updates the position of the component.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   **label-content** - A slot for rendering content next to the component's `labelText`.

### CSS Properties

*   **\--calcite-input-time-picker-background-color** - Specifies the component's background color.
*   **\--calcite-input-time-picker-border-color** - Specifies the component's border color.
*   **\--calcite-input-time-picker-icon-color** - Specifies the component's icon color.
*   **\--calcite-input-time-picker-icon-color-hover** - Specifies the component's icon color when hovered.
*   **\--calcite-input-time-picker-shadow** - Specifies the component's shadow.
*   **\--calcite-input-time-picker-corner-radius** - Specifies the component's border radius.
*   **\--calcite-input-time-picker-input-background-color** - Specifies the component's input background color.
*   **\--calcite-input-time-picker-input-text-color** - Specifies the component's input text color.
*   **\--calcite-input-time-picker-input-shadow** - Specifies the component's input shadow.
*   **\--calcite-input-time-picker-input-corner-radius** - Specifies the component's input border radius.
*   **\--calcite-input-time-picker-input-border-color** - Specifies the component's input border color.
*   **\--calcite-input-time-picker-digit-text-color** - Specifies the component's digit text color.
*   **\--calcite-input-time-picker-digit-icon-color** - Specifies the component's digit icon color.
*   **\--calcite-input-time-picker-digit-border-color-press** - Specifies the component's digit border color when pressed.
*   **\--calcite-input-time-picker-digit-border-color-hover** - Specifies the component's digit border color when hovered.
*   **\--calcite-input-time-picker-action-background-color-hover** - Specifies the background color of the component's actions when hovered or focused.
*   **\--calcite-input-time-picker-action-background-color-press** - Specifies the background color of the component's actions when active.

---

## calcite-input-time-zone

### Events

*   **calciteInputTimeZoneBeforeClose** - Fires when the component is requested to be closed and before the closing transition begins.
*   **calciteInputTimeZoneBeforeOpen** - Fires when the component is added to the DOM but not rendered, and before the opening transition begins.
*   **calciteInputTimeZoneChange** - Fires when the component's `value` changes.
*   **calciteInputTimeZoneClose** - Fires after the component is closed and animation is complete.
*   **calciteInputTimeZoneOpen** - Fires after the component is opened and animation is complete.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   **label-content** - A slot for rendering content next to the component's `labelText`.

---

## calcite-label

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding text and a component that can be labeled.

### CSS Properties

*   **\--calcite-label-margin-bottom** - Specifies the component's bottom spacing.
*   **\--calcite-label-text-color** - Specifies the component's text color.

---

## calcite-link

Any attributes placed on component will propagate to the rendered child.  
Passing a 'href' will render an anchor link, instead of a button.

## It is the consumers responsibility to add aria information, rel, target, for links, and any link attributes for form submission

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding text.

### CSS Properties

*   **\--calcite-link-text-color** - Specifies the component's text color.

---

## calcite-list

A general purpose list that enables users to construct list items that conform to Calcite styling.

### Events

*   **calciteListChange** - Fires when the component's selected items have changed.
*   **calciteListDragEnd** - Fires when the component's dragging has ended.
*   **calciteListDragStart** - Fires when the component's dragging has started.
*   **calciteListFilter** - Fires when the component's filter has changed.
*   **calciteListMoveHalt** - Fires when a user attempts to move an element using the sort menu and 'canPut' or 'canPull' returns falsy.
*   **calciteListOrderChange** - Fires when the component's item order changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

### Slots

*   _default_ - A slot for adding `calcite-list-item` and `calcite-list-item-group` elements.
*   **filter-actions-start** - A slot for adding actionable `calcite-action` elements before the filter component.
*   **filter-actions-end** - A slot for adding actionable `calcite-action` elements after the filter component.
*   **filter-no-results** - When `filterEnabled` is `true`, a slot for adding content to display when no results are found.

### CSS Properties

*   **\--calcite-list-background-color** - Specifies the component's background color.

---

## calcite-list-item

### Events

*   **calciteListItemClose** - Fires when the close button is clicked.
*   **calciteListItemCollapse** - Fires when the component's content area is collapsed.
*   **calciteListItemExpand** - Fires when the component's content area is expanded.
*   **calciteListItemSelect** - Fires when the component is selected.
*   **calciteListItemSortHandleBeforeClose** - Fires when the sort handle is requested to be closed and before the closing transition begins.
*   **calciteListItemSortHandleBeforeOpen** - Fires when the sort handle is added to the DOM but not rendered, and before the opening transition begins.
*   **calciteListItemSortHandleClose** - Fires when the sort handle is closed and animation is complete.
*   **calciteListItemSortHandleOpen** - Fires when the sort handle is open and animation is complete.
*   **calciteListItemToggle** - Fires when the open button is clicked.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding `calcite-list`, `calcite-list-item` and `calcite-list-item-group` elements.
*   **actions-start** - A slot for adding actionable `calcite-action` elements before the content of the component.
*   **content-start** - A slot for adding non-actionable elements before the label and description of the component.
*   **content** - A slot for adding non-actionable, centered content in place of the `label` and `description` of the component.
*   **content-end** - A slot for adding non-actionable elements after the label and description of the component.
*   **actions-end** - A slot for adding actionable `calcite-action` elements after the content of the component.
*   **content-bottom** - A slot for adding content below the component's `label` and `description`.

### CSS Properties

*   **\--calcite-list-background-color-hover** - Specifies the component's background color when hovered.
*   **\--calcite-list-background-color-press** - Specifies the component's background color when pressed.
*   **\--calcite-list-background-color** - Specifies the component's background color.
*   **\--calcite-list-border-color** - Specifies the component's border color.
*   **\--calcite-list-content-text-color** - Specifies the content color.
*   **\--calcite-list-description-text-color** - Specifies the `description` color.
*   **\--calcite-list-icon-color** - Specifies the component's icon color.
*   **\--calcite-list-label-text-color** - Specifies the `label` color.
*   **\--calcite-list-selection-border-color** - Specifies the component's selection border color.

---

## calcite-list-item-

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding `calcite-list-item` and `calcite-list-item-group` elements.

### CSS Properties

*   **\--calcite-list-background-color** - Specifies the component's background color.
*   **\--calcite-list-color** - Specifies the component's color.

---

## calcite-loader

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### CSS Properties

*   **\--calcite-loader-font-size** - When `type` is not `"indeterminate"` or `inline`, specifies the font size of the loading percentage.
*   **\--calcite-loader-size** - Specifies the component's width and height.
*   **\--calcite-loader-size-inline** - \[Deprecated\] Use `--calcite-loader-size`. Specifies the width and height of the component when set to inline.
*   **\--calcite-loader-spacing** - Specifies the the component's padding.
*   **\--calcite-loader-progress-color-inline** - When `inline`, specifies the component's progress ring color.
*   **\--calcite-loader-text-spacing** - When not `inline`, specifies the component's `text` margin.
*   **\--calcite-loader-text-weight** - When not `inline` and `text` is provided, specifies the component's `text` font weight.
*   **\--calcite-loader-text-color** - When not `inline` and `text` is provided, specifies the component's `text` color.
*   **\--calcite-loader-progress-color** - When not `inline`, specifies the component's progress ring color.
*   **\--calcite-loader-track-color** - Specifies the component's track color.

---

## calcite-menu

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

---

## calcite-menu-item

### Events

*   **calciteMenuItemSelect** - Emits when the component is selected.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   **submenu-item** - A slot for adding `calcite-menu-item`s in a submenu.

### CSS Properties

*   **\--calcite-menu-item-accent-color** - Specifies the border color of the component when `active`.
*   **\--calcite-menu-background-color** - Specifies the background color of the component.
*   **\--calcite-menu-item-sub-menu-border-color** - Specifies the border color of sub-menu.
*   **\--calcite-menu-item-sub-menu-corner-radius** - Specifies the border radius of sub-menu.
*   **\--calcite-menu-text-color** - Specifies the text color of the component.

---

## calcite-meter

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### CSS Properties

*   **\--calcite-meter-background-color** - Specifies the background color of the component.
*   **\--calcite-meter-border-color** - Specifies the border color of the component and displayed step lines.
*   **\--calcite-meter-shadow** - Specifies the box shadow of the component.
*   **\--calcite-meter-corner-radius** - Specifies the corner radius of the component.
*   **\--calcite-meter-fill-color** - Specifies the color of the component's fill.
*   **\--calcite-meter-range-text-color** - Specifies the color of the component's range labels.
*   **\--calcite-meter-value-text-color** - Specifies the color of the component's value label.

---

## calcite-modal

**Deprecated**: Use the `calcite-dialog` component instead..

### Events

*   **calciteModalBeforeClose** - Fires when the component is requested to be closed and before the closing transition begins.
*   **calciteModalBeforeOpen** - Fires when the component is added to the DOM but not rendered, and before the opening transition begins.
*   **calciteModalClose** - Fires when the component is closed and animation is complete.
*   **calciteModalOpen** - Fires when the component is open and animation is complete.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `scrollContent(top?: number, left?: number): Promise` - Sets the scroll top of the component's content.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's "close" button (the first focusable item).
*   `updateFocusTrapElements(extraContainers?: FocusTrapOptions\["extraContainers"\]): Promise` - Updates the element(s) that are included in the focus-trap of the component.

### Slots

*   **header** - A slot for adding header text.
*   **content** - A slot for adding the component's content.
*   **content-top** - A slot for adding content to the component's sticky header, where content remains at the top of the component when scrolling up and down.
*   **content-bottom** - A slot for adding content to the component's sticky footer, where content remains at the bottom of the component when scrolling up and down.
*   **primary** - A slot for adding a primary button.
*   **secondary** - A slot for adding a secondary button.
*   **back** - A slot for adding a back button.

### CSS Properties

*   **\--calcite-modal-content-background** - Specifies the background color of content placed in the component's `"content"` slot.
*   **\--calcite-modal-content-padding** - Specifies the padding of the component's `"content"` slot.
*   **\--calcite-modal-scrim-background** - Specifies the background color of the component's scrim.
*   **\--calcite-modal-width** - Specifies the width of the component, using `px`, `em`, `rem`, `vw`, or `%`. Will never exceed the width of the viewport. Will not apply if `fullscreen` if set.
*   **\--calcite-modal-height** - Specifies the height of the component, using `px`, `em`, `rem`, `vh`, or `%`. Will never exceed the height of the viewport. Will not apply if `fullscreen` if set.

---

## calcite-navigation

### Events

*   **calciteNavigationActionSelect** - When `navigationAction` is `true`, emits when the displayed action selection changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - When `navigationAction` is `true` , sets focus on the component's action element.

### Slots

*   **logo** - A slot for adding a `calcite-logo` component to the primary navigation level.
*   **user** - A slot for adding a `calcite-user` component to the primary navigation level.
*   **progress** - A slot for adding a `calcite-progress` component to the primary navigation level.
*   **navigation-action** - A slot for adding a `calcite-action` component to the primary navigation level.
*   **content-start** - A slot for adding a `calcite-menu`, `calcite-action`, or other interactive elements in the start position of any navigation level.
*   **content-center** - A slot for adding a `calcite-menu`, `calcite-action`, or other interactive elements in the center position of the primary navigation level.
*   **content-end** - A slot for adding a `calcite-menu`, `calcite-action`, or other interactive elements in the end position of any navigation level.
*   **navigation-secondary** - A slot for adding a `calcite-navigation` component in the secondary navigation level. Components rendered here will not display `calcite-navigation-logo` or `calcite-navigation-user` components.
*   **navigation-tertiary** - A slot for adding a `calcite-navigation` component in the tertiary navigation level. Components rendered here will not display `calcite-navigation-logo` or `calcite-navigation-user` components.

### CSS Properties

*   **\--calcite-navigation-width** - Specifies the width of the component's content area.
*   **\--calcite-navigation-background** - \[Deprecated\] Use `--calcite-navigation-background-color`. Specifies the background color of the component.
*   **\--calcite-navigation-background-color** - Specifies the component's background color.
*   **\--calcite-navigation-border-color** - Specifies the component's border color.

---

## calcite-navigation-logo

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### CSS Properties

*   **\--calcite-navigation-accent-color** - Specifies the component's border color when `active`.
*   **\--calcite-navigation-background-color** - Specifies the component's background color.
*   **\--calcite-navigation-logo-heading-text-color** - Specifies the component's default color for heading text.
*   **\--calcite-navigation-logo-text-color** - Specifies the component's default color for icon and description text.

---

## calcite-navigation-user

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### CSS Properties

*   **\--calcite-navigation-accent-color** - Specifies the components's border color when `active`.
*   **\--calcite-navigation-user-avatar-corner-radius** - Specifies the component's avatar corner radius.
*   **\--calcite-navigation-user-avatar-color** - Specifies the component's avatar icon color.
*   **\--calcite-navigation-background-color** - Specifies the component's background color.
*   **\--calcite-navigation-user-full-name-text-color** - Specifies the component's `fullName` text color.
*   **\--calcite-navigation-user-name-text-color** - Specifies the component's `username` text color.

---

## calcite-notice

Notices are intended to be used to present users with important-but-not-crucial contextual tips or copy. Because notices are displayed inline, a common use case is displaying them on page-load to present users with short hints or contextual copy.  
They are optionally closable - useful for keeping track of whether or not a user has closed the notice. You can also choose not to display a notice on page load and set the "active" attribute as needed to contextually provide inline messaging to users.

### Events

*   **calciteNoticeBeforeClose** - Fires when the component is requested to be closed and before the closing transition begins.
*   **calciteNoticeBeforeOpen** - Fires when the component is added to the DOM but not rendered, and before the opening transition begins.
*   **calciteNoticeClose** - Fires when the component is closed and animation is complete.
*   **calciteNoticeOpen** - Fires when the component is open and animation is complete.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

### Slots

*   **title** - A slot for adding the title.
*   **message** - A slot for adding the message.
*   **link** - A slot for adding a `calcite-action` to take, such as: "undo", "try again", "link to page", etc.
*   **actions-end** - A slot for adding `calcite-action`s to the end of the component. It is recommended to use two or less actions.

### CSS Properties

*   **\--calcite-notice-background-color** - Specifies the component's background color.
*   **\--calcite-notice-close-background-color-focus** - Specifies the component's background color when focused.
*   **\--calcite-notice-close-background-color-press** - Specifies the component's background color when active.
*   **\--calcite-notice-close-icon-color-hover** - Specifies the background color of the component's close button when hovered.
*   **\--calcite-notice-close-icon-color** - Specifies the text color of the component's close button.
*   **\--calcite-notice-title-text-color** - Specifies the component's title text color.
*   **\--calcite-notice-content-text-color** - Specifies the component's content text color.
*   **\--calcite-notice-width** - \[Deprecated\] Specifies the component's width.
*   **\--calcite-notice-close-text-color-hover** - \[Deprecated\] Use `--calcite-notice-close-icon-color-hover`. Specifies the background color of the component's close button when hovered.
*   **\--calcite-notice-close-text-color** - \[Deprecated\] Use `--calcite-notice-close-icon-color`. Specifies the text color of the component's close button.

---

## calcite-option

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

---

## calcite-option-group

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding `calcite-option`s.

---

## calcite-pagination

### Events

*   **calcitePaginationChange** - Emits when the selected page changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   \`goTo(page: number

---

## calcite-panel

### Events

*   **calcitePanelClose** - Fires when the close button is clicked.
*   **calcitePanelCollapse** - Fires when the component's content area is collapsed.
*   **calcitePanelExpand** - Fires when the component's content area is expanded.
*   **calcitePanelScroll** - Fires when the content is scrolled.
*   **calcitePanelToggle** - Fires when the collapse button is clicked.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `scrollContentTo(options?: ScrollToOptions): Promise` - Scrolls the component's content to a specified set of coordinates.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

### Slots

*   _default_ - A slot for adding custom content.
*   **action-bar** - A slot for adding a `calcite-action-bar` to the component.
*   **alerts** - A slot for adding `calcite-alert` s to the component.
*   **content-bottom** - A slot for adding content below the unnamed (default) slot and above the footer slot (if populated)
*   **content-top** - A slot for adding content above the unnamed (default) slot and below the action-bar slot (if populated).
*   **header-actions-start** - A slot for adding actions or content to the start side of the header.
*   **header-actions-end** - A slot for adding actions or content to the end side of the header.
*   **header-content** - A slot for adding custom content to the header.
*   **header-menu-actions** - A slot for adding an overflow menu with actions inside a `calcite-dropdown` .
*   **fab** - A slot for adding a `calcite-fab` (floating action button) to perform an action.
*   **footer** - A slot for adding custom content to the component's footer. Should not be used with the `"footer-start"` or `"footer-end"` slots.
*   **footer-actions** - \[Deprecated\] Use the `footer-start` and `footer-end` slots instead. A slot for adding `calcite-button` s to the component's footer.
*   **footer-end** - A slot for adding a trailing footer custom content. Should not be used with the `"footer"` slot.
*   **footer-start** - A slot for adding a leading footer custom content. Should not be used with the `"footer"` slot.

### CSS Properties

*   **\--calcite-panel-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-panel-heading-text-color** - Specifies the text color of the component's `heading`.
*   **\--calcite-panel-icon-color** - Specifies the color of the component's icon.
*   **\--calcite-panel-description-text-color** - Specifies the text color of the component's `description`.
*   **\--calcite-panel-border-color** - Specifies the component's border color.
*   **\--calcite-panel-background-color** - Specifies the component's background color.
*   **\--calcite-panel-header-background-color** - Specifies the background color of the component's header.
*   **\--calcite-panel-header-action-background-color** - Specifies the background color of Panel's `closable`, `collapsible`, and elements slotted in `header-menu-actions`.
*   **\--calcite-panel-header-action-background-color-hover** - Specifies the background color of Panel's `closable`, `collapsible`, and elements slotted in `header-menu-actions` when hovered.
*   **\--calcite-panel-header-action-background-color-press** - Specifies the background color of Panel's `closable`, `collapsible`, and elements slotted in `header-menu-actions` when pressed.
*   **\--calcite-panel-header-action-text-color** - Specifies the text color of Panel's `closable`, `collapsible`, and elements slotted in `header-menu-actions`.
*   **\--calcite-panel-header-action-text-color-press** - Specifies the text color of Panel's `closable`, `collapsible`, and elements slotted in `header-menu-actions` when pressed or hovered.
*   **\--calcite-panel-footer-background-color** - Specifies the background color of the component's footer.
*   **\--calcite-panel-space** - Specifies the padding of the component's `"unnamed (default)"` slot.
*   **\--calcite-panel-header-content-space** - Specifies the padding of the `"header-content"` slot.
*   **\--calcite-panel-footer-space** - Specifies the padding of the component's footer.
*   **\--calcite-popover-border-color** - Specifies the border color of the component's internally rendered `calcite-popover`, which is rendered within a `calcite-action` menu when slotted `calcite-action`s are present in the `header-actions-end` slot. Applies to any slotted `calcite-popover`s.
*   **\--calcite-panel-content-space** - \[Deprecated\] Use `--calcite-panel-space` instead. Specifies the padding of the component's content.
*   **\--calcite-panel-footer-padding** - \[Deprecated\] Use `--calcite-panel-footer-space` instead. Specifies the padding of the component's footer.
*   **\--calcite-panel-header-border-block-end** - \[Deprecated\] Use `--calcite-panel-border-color` instead. Specifies the component header's block end border.

---

## calcite-popover

### Events

*   **calcitePopoverBeforeClose** - Fires when the component is requested to be closed and before the closing transition begins.
*   **calcitePopoverBeforeOpen** - Fires when the component is added to the DOM but not rendered, and before the opening transition begins.
*   **calcitePopoverClose** - Fires when the component is closed and animation is complete.
*   **calcitePopoverOpen** - Fires when the component is open and animation is complete.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `reposition(delayed?: boolean): Promise` - Updates the position of the component.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.
*   `updateFocusTrapElements(): Promise` - Updates the element(s) that are used within the focus-trap of the component.

### Slots

*   _default_ - A slot for adding custom content.

### CSS Properties

*   **\--calcite-popover-background-color** - Specifies the component's background color.
*   **\--calcite-popover-border-color** - Specifies the component's border color.
*   **\--calcite-popover-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-popover-max-size-x** - Specifies the component's maximum width.
*   **\--calcite-popover-text-color** - Specifies the component's text color.
*   **\--calcite-popover-z-index** - Specifies the component's z-index value.

---

## calcite-progress

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### CSS Properties

*   **\--calcite-progress-background-color** - Specifies the component's background color.
*   **\--calcite-progress-fill-color** - Specifies the component's fill color.
*   **\--calcite-progress-text-color** - Specifies the component's text color.

---

## calcite-radio-button

### Events

*   **calciteRadioButtonChange** - Fires only when the radio button is checked. This behavior is identical to the native HTML input element.  
    Since this event does not fire when the radio button is unchecked, it's not recommended to attach a listener for this event  
    directly on the element, but instead either attach it to a node that contains all of the radio buttons in the group  
    or use the `calciteRadioButtonGroupChange` event if using this with `calcite-radio-button-group` .

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### CSS Properties

*   **\--calcite-radio-button-background-color** - Specifies the component's background color.
*   **\--calcite-radio-button-border-color** - Specifies the component's border color.
*   **\--calcite-radio-button-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-radio-button-size** - Specifies the component's size.
*   **\--calcite-radio-size** - \[Deprecated\] Use `--calcite-radio-button-size`. Specifies the component's size.

---

## calcite-radio-button-group

### Events

*   **calciteRadioButtonGroupChange** - Fires when the component has changed.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the fist focusable `calcite-radio-button` element in the component.

### Slots

*   _default_ - A slot for adding `calcite-radio-button` s.
*   **label-content** - A slot for rendering content next to the component's `labelText`.

### CSS Properties

*   **\--calcite-radio-button-group-gap** - Specifies the space between slotted components in the component.
*   **\--calcite-radio-button-input-message-spacing** - Specifies the margin spacing at the top of the input-message component.

---

## calcite-rating

### Events

*   **calciteRatingChange** - Fires when the component's value changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   **label-content** - A slot for rendering content next to the component's `labelText`.

### CSS Properties

*   **\--calcite-rating-spacing-unit** - \[Deprecated\] Use `--calcite-rating-spacing`. Specifies the amount of left and right margin spacing between each item.
*   **\--calcite-rating-spacing** - Specifies the amount of left and right margin spacing between each item.
*   **\--calcite-rating-color-hover** - Specifies the component's item color when hovered.
*   **\--calcite-rating-color-press** - Specifies the component's item color when active.
*   **\--calcite-rating-color** - Specifies the component's item color.
*   **\--calcite-rating-average-color** - Specifies the component's item color when average is set.
*   **\--calcite-rating-average-text-color** - Specifies the component's average text color.
*   **\--calcite-rating-count-text-color** - Specifies the component's count text color.

---

## calcite-scrim

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding custom content, primarily loading information.

### CSS Properties

*   **\--calcite-scrim-background** - Specifies the background color of the scrim.

---

## calcite-segmented-control

### Events

*   **calciteSegmentedControlChange** - Fires when the `calcite-segmented-control-item` selection changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding `calcite-segmented-control-item` s.
*   **label-content** - A slot for rendering content next to the component's `labelText`.

### CSS Properties

*   **\--calcite-segmented-control-border-color** - Specifies the component's border color.

---

## calcite-segmented-control-item

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### CSS Properties

*   **\--calcite-segmented-control-color** - Specifies the component's color.
*   **\--calcite-segmented-control-background-color** - Specifies the component's background color.
*   **\--calcite-segmented-control-border-color** - Specifies the component's border color.
*   **\--calcite-segmented-control-shadow** - Specifies the component's shadow.
*   **\--calcite-segmented-control-icon-color** - Specifies the icons's color.

---

## calcite-select

### Events

*   **calciteSelectChange** - Fires when the `selectedOption` changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding `calcite-option`s.
*   **label-content** - A slot for rendering content next to the component's `labelText`.

### CSS Properties

*   **\--calcite-select-font-size** - Specifies the font size of `calcite-option`s in the component.
*   **\--calcite-select-text-color** - Specifies the text color of `calcite-option`s in the component.
*   **\--calcite-select-border-color** - Specifies the component's border color.
*   **\--calcite-select-icon-color** - Specifies the component's icon color.
*   **\--calcite-select-icon-color-hover** - Specifies the component's icon color when hovered or active.
*   **\--calcite-select-background-color** - Specifies the component's background color.
*   **\--calcite-select-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-select-shadow** - Specifies the component's shadow.

---

## calcite-sheet

### Events

*   **calciteSheetBeforeClose** - Fires when the component is requested to be closed and before the closing transition begins.
*   **calciteSheetBeforeOpen** - Fires when the component is added to the DOM but not rendered, and before the opening transition begins.
*   **calciteSheetClose** - Fires when the component is closed and animation is complete.
*   **calciteSheetOpen** - Fires when the component is open and animation is complete.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's "close" button - the first focusable item.
*   `updateFocusTrapElements(extraContainers?: FocusTrapOptions\["extraContainers"\]): Promise` - Updates the element(s) that are included in the focus-trap of the component.

### Slots

*   _default_ - A slot for adding custom content.

### CSS Properties

*   **\--calcite-sheet-background-color** - Specifies the background color of the sheet.
*   **\--calcite-sheet-corner-radius** - Specifies the corner radius of the component.
*   **\--calcite-sheet-shadow** - Specifies the shadow of the component.
*   **\--calcite-sheet-text-color** - Specifies the text color of the component.
*   **\--calcite-sheet-resize-background-color** - Specifies the background color of the resize handle.
*   **\--calcite-sheet-resize-icon-color** - Specifies the text color of the resize handle.
*   **\--calcite-sheet-scrim-background** - Specifies the background color of the sheet scrim.
*   **\--calcite-sheet-width** - When `position` is `"inline-start"` or `"inline-end"`, specifies the width of the component.
*   **\--calcite-sheet-max-width** - When `position` is `"inline-start"` or `"inline-end"`, specifies the maximum width of the component.
*   **\--calcite-sheet-min-width** - When `position` is `"inline-start"` or `"inline-end"`, specifies the minimum width of the component.
*   **\--calcite-sheet-height** - When `position` is `"block-start"` or `"block-end"`, specifies the height of the component.
*   **\--calcite-sheet-max-height** - When `position` is `"block-start"` or `"block-end"`, specifies the maximum height of the component.
*   **\--calcite-sheet-min-height** - When `position` is `"block-start"` or `"block-end"`, specifies the minimum height of the component.

---

## calcite-shell

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding custom content. This content will appear between any leading and trailing panels added to the component, such as a map.
*   **header** - A slot for adding header content. This content will be positioned at the top of the component.
*   **footer** - A slot for adding footer content. This content will be positioned at the bottom of the component.
*   **panel-start** - A slot for adding the starting `calcite-shell-panel` .
*   **panel-end** - A slot for adding the ending `calcite-shell-panel` .
*   **panel-top** - A slot for adding the top `calcite-shell-panel` .
*   **panel-bottom** - A slot for adding the bottom `calcite-shell-panel` .
*   **center-row** - \[Deprecated\] Use the `"panel-bottom"` slot instead. A slot for adding the bottom `calcite-shell-center-row` .
*   **modals** - A slot for adding `calcite-modal` components. When placed in this slot, the modal position will be constrained to the extent of the `calcite-shell` .
*   **dialogs** - A slot for adding `calcite-dialog` components. When placed in this slot, the dialog position will be constrained to the extent of the `calcite-shell` .
*   **alerts** - A slot for adding `calcite-alert` components. When placed in this slot, the alert position will be constrained to the extent of the `calcite-shell` .
*   **sheets** - A slot for adding `calcite-sheet` components. When placed in this slot, the sheet position will be constrained to the extent of the `calcite-shell` .

### CSS Properties

*   **\--calcite-shell-border-color** - Specifies the component's border color.
*   **\--calcite-shell-tip-spacing** - \[Deprecated\] This component has been deprecated. The left and right spacing of the `calcite-tip-manager` when slotted in the component.

---

## calcite-shell-center-row

**Deprecated**: Use the `calcite-shell-panel` component instead..

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding content to the `calcite-shell-panel`.
*   **action-bar** - A slot for adding a `calcite-action-bar` to the `calcite-shell-panel`.

---

## calcite-shell-panel

### Events

*   **calciteShellPanelCollapse** - Fires when the component's content area is collapsed.
*   **calciteShellPanelExpand** - Fires when the component's content area is expanded.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding custom content.
*   **action-bar** - A slot for adding a `calcite-action-bar` to the component.

### CSS Properties

*   **\--calcite-shell-panel-background-color** - Specifies the background color of the component.
*   **\--calcite-shell-panel-border-color** - When `displayMode` is `"float-all"`, specifies the component's border color.
*   **\--calcite-shell-panel-corner-radius** - When `displayMode` is `"float-all"`, specifies the component's corner radius.
*   **\--calcite-shell-panel-height** - When `layout` is `horizontal`, or `layout` is `vertical` and `displayMode` is `float-content` or `float`, specifies the height of the component.
*   **\--calcite-shell-panel-max-height** - When `layout` is `horizontal`, or `layout` is `vertical` and `displayMode` is `float-content` or `float`, specifies the maximum height of the component.
*   **\--calcite-shell-panel-max-width** - Specifies the maximum width of the component.
*   **\--calcite-shell-panel-min-height** - When `layout` is `horizontal`, or `layout` is `vertical` and `displayMode` is `float-content` or `float`, specifies the minimum height of the component.
*   **\--calcite-shell-panel-min-width** - Specifies the minimum width of the component.
*   **\--calcite-shell-panel-resize-background-color** - Specifies the background color of the resize handle.
*   **\--calcite-shell-panel-resize-icon-color** - Specifies the text color of the resize handle.
*   **\--calcite-shell-panel-shadow** - When `displayMode` is `"float-all"`, specifies the component's shadow.
*   **\--calcite-shell-panel-text-color** - Specifies the text color of the component.
*   **\--calcite-shell-panel-width** - Specifies the width of the component.
*   **\--calcite-shell-panel-z-index** - Specifies the z-index value for the component.

---

## calcite-slider

### Events

*   **calciteSliderChange** - Fires when the thumb is released on the component.

Note: To constantly listen to the drag event,  
use `calciteSliderInput` instead.

*   **calciteSliderInput** - Fires on all updates to the component.

Note: Fires frequently during drag. To perform  
expensive operations consider using a debounce or throttle to avoid  
locking up the main thread.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   **label-content** - A slot for rendering content next to the component's `labelText`.

### CSS Properties

*   **\--calcite-slider-text-color** - Specifies the component's text color.
*   **\--calcite-slider-track-color** - Specifies the component's track color.
*   **\--calcite-slider-track-fill-color** - Specifies the component's track fill color.
*   **\--calcite-slider-handle-fill-color** - Specifies the component's handle fill color.
*   **\--calcite-slider-handle-extension-color** - Specifies the component's handle extension color.
*   **\--calcite-slider-accent-color** - Specifies the component's accent color.
*   **\--calcite-slider-tick-color** - Specifies the component's tick color.
*   **\--calcite-slider-tick-border-color** - Specifies the component's tick border color.
*   **\--calcite-slider-tick-selected-color** - Specifies the component's tick color when in selected range.
*   **\--calcite-slider-graph-color** - Specifies the component's graph color.

---

## calcite-sort-handle

### Events

*   **calciteSortHandleAdd** - Fires when an add item has been selected.
*   **calciteSortHandleBeforeClose** - Fires when the component is requested to be closed and before the closing transition begins.
*   **calciteSortHandleBeforeOpen** - Fires when the component is added to the DOM but not rendered, and before the opening transition begins.
*   **calciteSortHandleClose** - Fires when the component is closed and animation is complete.
*   **calciteSortHandleMove** - Fires when a move item has been selected.
*   **calciteSortHandleOpen** - Fires when the component is open and animation is complete.
*   **calciteSortHandleReorder** - Fires when a reorder has been selected.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

---

## calcite-sortable-list

**Deprecated**: Use the `calcite-block-group` component instead..

### Events

*   **calciteListOrderChange** - Emitted when the order of the list has changed.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding sortable items.

---

## calcite-split-button

### Events

*   **calciteSplitButtonPrimaryClick** - Fires when the primary button is clicked.
*   **calciteSplitButtonSecondaryClick** - Fires when the dropdown menu is clicked.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

### Slots

*   _default_ - A slot for adding `calcite-dropdown` content.

### CSS Properties

*   **\--calcite-split-button-background-color** - Specifies the component's background color.
*   **\--calcite-split-button-border-color** - Specifies the component's border color.
*   **\--calcite-split-button-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-split-button-icon-color** - Specifies the component's `iconStart` and
*   **\--calcite-split-button-loader-color** - Specifies the component's loader color.
*   **\--calcite-split-button-text-color** - Specifies the component's text color.
*   **\--calcite-split-button-shadow** - Specifies the component's shadow.
*   **\--calcite-split-button-divider-border-color** - Specifies the component's divider border color.
*   **\--calcite-split-button-divider-color** - Specifies the component's divider color.
*   **\--calcite-split-button-dropdown-width** - Specifies the width of the component's dropdown.
*   **\--calcite-split-button-dropdown-background-color** - Specifies the component's dropdown background color.  
    \*

---

## calcite-stack

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding content.
*   **actions-start** - A slot for adding actionable `calcite-action` elements before the content of the component.
*   **content-start** - A slot for adding non-actionable elements before content of the component.
*   **content-end** - A slot for adding non-actionable elements after content of the component.
*   **actions-end** - A slot for adding actionable `calcite-action` elements after the content of the component.

### CSS Properties

*   **\--calcite-stack-padding-inline** - Specifies the inline padding of the component's content.
*   **\--calcite-stack-padding-block** - Specifies the block padding of the component's content.

---

## calcite-stepper

### Events

*   **calciteStepperChange** - Fires when the active `calcite-stepper-item` changes.
*   **calciteStepperItemChange** - Fires when the active `calcite-stepper-item` changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `endStep(): Promise` - Set the last `calcite-stepper-item` as active.
*   `goToStep(step: number): Promise` - Set a specified `calcite-stepper-item` as active.
*   `nextStep(): Promise` - Set the next `calcite-stepper-item` as active.
*   `prevStep(): Promise` - Set the previous `calcite-stepper-item` as active.
*   `startStep(): Promise` - Set the first `calcite-stepper-item` as active.

### Slots

*   _default_ - A slot for adding `calcite-stepper-item` elements.

### CSS Properties

*   **\--calcite-stepper-bar-gap** - Specifies the space between items in the component.
*   **\--calcite-stepper-bar-inactive-fill-color** - Specifies the fill color of items in the component.
*   **\--calcite-stepper-bar-active-fill-color** - Specifies the fill color of active items in the component.
*   **\--calcite-stepper-bar-complete-fill-color** - Specifies the fill color of complete items in the component.
*   **\--calcite-stepper-bar-error-fill-color** - Specifies the fill color of error items in the component.

---

## calcite-stepper-item

### Events

*   **calciteStepperItemSelect** - Fires when the active `calcite-stepper-item` changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding custom content.

### CSS Properties

*   **\--calcite-stepper-item-background-color-press** - Specifies the component's background-color when active.
*   **\--calcite-stepper-item-header-text-color** - Specifies the component's header text color.
*   **\--calcite-stepper-item-header-text-color-hover** - Specifies the component's header text color when hovered or focused.
*   **\--calcite-stepper-item-selected-header-text-color** - Specifies the component's header text color when selected.
*   **\--calcite-stepper-item-icon-color** - Specifies the component's icon color.
*   **\--calcite-stepper-item-complete-icon-color** - Specifies the component's icon color when complete.
*   **\--calcite-stepper-item-error-icon-color** - Specifies the component's icon and number color when in error.
*   **\--calcite-stepper-item-selected-icon-color** - Specifies the component's icon and number color when selected.
*   **\--calcite-stepper-item-description-text-color** - Specifies the component's description and number text color.
*   **\--calcite-stepper-item-description-text-color-hover** - Specifies the component's description text color when hovered, focused or selected.
*   **\--calcite-stepper-bar-gap** - Specifies the component's bottom spacing.
*   **\--calcite-stepper-bar-fill-color** - Specifies the component's fill color.
*   **\--calcite-stepper-bar-fill-color-hover** - Specifies the component's fill color when hovered or focused.
*   **\--calcite-stepper-bar-complete-fill-color** - Specifies the component's fill color when complete.
*   **\--calcite-stepper-bar-complete-fill-color-hover** - When the component is `complete`, specifies the component's fill color when hovered or focused.
*   **\--calcite-stepper-bar-error-fill-color** - Specifies the component's fill color when in error.
*   **\--calcite-stepper-bar-error-fill-color-hover** - When the component contains an `error`, specifies the component's fill color when hovered or focused.
*   **\--calcite-stepper-bar-selected-fill-color** - Specifies the component's fill color when selected.

---

## calcite-swatch

### Events

*   **calciteSwatchSelect** - Fires when the selected state of the component changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### CSS Properties

*   **\--calcite-swatch-corner-radius** - Specifies the component's corner radius.

---

## calcite-swatch-group

### Events

*   **calciteSwatchGroupSelect** - Fires when the component's selection changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

### Slots

*   _default_ - A slot for adding one or more `calcite-swatch`s.

### CSS Properties

*   **\--calcite-swatch-group-space** - Specifies the space between slotted elements.

---

## calcite-switch

### Events

*   **calciteSwitchChange** - Fires when the `checked` value has changed.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### CSS Properties

*   **\--calcite-switch-background-color** - Specifies the component's background color.
*   **\--calcite-switch-background-color-hover** - Specifies the component's background color when hovered or pressed.
*   **\--calcite-switch-border-color** - \[Deprecated\] No longer necessary. Specifies the component's border color.
*   **\--calcite-switch-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-switch-handle-background-color** - Specifies the handle's background color.
*   **\--calcite-switch-handle-border-color** - \[Deprecated\] No longer necessary. Specifies the handle's border color.
*   **\--calcite-switch-handle-shadow** - \[Deprecated\] No longer necessary. Specifies the handle's shadow.

---

## calcite-tab

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `getTabIndex(): Promise` - Returns the index of the component item within the tab array.

### Slots

*   _default_ - A slot for adding custom content.

### CSS Properties

*   **\--calcite-tab-content-space-y** - Specifies the vertical space between the component's content in the `default` slot.
*   **\--calcite-tab-content-block-padding** - \[Deprecated\] Use `--calcite-tab-content-space-y` instead. Specifies the block padding of the component's content in the `default` slot.

---

## calcite-tab-nav

### Events

*   **calciteTabChange** - Emits when the selected `calcite-tab` changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding `calcite-tab-title`s.

### CSS Properties

*   **\--calcite-tab-background-color** - When `calcite-tabs` is `bordered`, specifies the component's background color.
*   **\--calcite-tab-border-color** - When `calcite-tabs` is `bordered`, specifies the component's border color.
*   **\--calcite-tab-text-color** - Specifies the component's `iconStart,` iconEnd\`, and text color.

---

## calcite-tab-title
Tab-titles are optionally individually closable.

### Events

*   **calciteTabsActivate** - Fires when a `calcite-tab` is selected.
*   **calciteTabsClose** - Fires when a `calcite-tab` is closed.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `getTabIndex(): Promise` - Returns the index of the title within the `calcite-tab-nav` .

### Slots

*   _default_ - A slot for adding text.

### CSS Properties

*   **\--calcite-tab-text-color** - Specifies the component's text color.
*   **\--calcite-tab-border-color** - Specifies the component's border color.
*   **\--calcite-tab-background-color** - Specifies the component's background color.
*   **\--calcite-tab-background-color-hover** - When `calcite-tabs` is `bordered`, specifies the component's background color when hovered.
*   **\--calcite-tab-accent-color-press** - Specifies the component's accent color when selected or active.
*   **\--calcite-tab-icon-color-end** - Specifies the component's `iconEnd` color. Fallback to `--calcite-icon-color`.
*   **\--calcite-tab-icon-color-start** - Specifies the component's `iconStart` color. Fallback to `--calcite-icon-color`.
*   **\--calcite-tab-close-icon-color** - Specifies the component's close element icon color.
*   **\--calcite-tab-close-icon-color-press** - Specifies the component's close element icon color when hovered, focused, and active.
*   **\--calcite-tab-close-icon-background-color** - Specifies the component's close element icon background color.
*   **\--calcite-tab-close-icon-background-color-press** - Specifies the component's close element icon background color when hovered, focused, and active.

---

## calcite-table

### Events

*   **calciteTablePageChange** - Emits when the component's page selection changes.
*   **calciteTableSelect** - Emits when the component's selected rows change.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding `calcite-table-row` elements containing `calcite-table-cell` and/or `calcite-table-header` elements.
*   **table-header** - A slot for adding `calcite-table-row` elements containing `calcite-table-header` elements.
*   **table-footer** - A slot for adding `calcite-table-row` elements containing `calcite-table-cell` and/or `calcite-table-header` elements.
*   **selection-actions** - A slot for adding `calcite-actions` or other elements to display when `selectionMode` is not `"none"` and `selectionDisplay` is not `"none"`.

### CSS Properties

*   **\--calcite-table-border-color** - Specifies the component's border color.
*   **\--calcite-table-corner-radius** - Specifies the component's border radius.
*   **\--calcite-table-shadow** - Specifies the component's shadow.
*   **\--calcite-table-number-cell-background-color** - Specifies the background color of the component's `numbered` cell.
*   **\--calcite-table-number-cell-text-color** - Specifies the text color of the component's `numbered` cell.
*   **\--calcite-table-selection-cell-background-color** - Specifies the background color of the component's `selectionMode` cell.
*   **\--calcite-table-selection-cell-background-color-selected** - Specifies the background color of the component's `selectionMode` cell.
*   **\--calcite-table-selection-cell-icon-color** - Specifies the icon color of the component's `selectionMode` selection icon.
*   **\--calcite-table-selection-cell-icon-color-selected** - Specifies the icon color of the component's `selectionMode` selection icon when selected.
*   **\--calcite-table-selection-chip-background-color** - Specifies the background color of the component's `selectionMode` selection chip.
*   **\--calcite-table-selection-chip-border-color** - Specifies the border color of the component's `selectionMode` selection chip.
*   **\--calcite-table-selection-chip-corner-radius** - Specifies the corner radius of the component's `selectionMode` selection chip.
*   **\--calcite-table-selection-chip-shadow** - Specifies the shadow of the component's `selectionMode` selection chip.
*   **\--calcite-table-selection-chip-text-color** - Specifies the text color of the component's `selectionMode` selection chip.
*   **\--calcite-table-selection-chip-background-color-selected** - Specifies the background color of the component's `selectionMode` selection chip when Table Rows are selected.
*   **\--calcite-table-selection-chip-border-color-selected** - Specifies the border color of the component's `selectionMode` selection chip when Table Rows are selected.
*   **\--calcite-table-selection-chip-text-color-selected** - Specifies the text color of the component's `selectionMode` selection chip when Table Rows are selected.
*   **\--calcite-table-selection-out-of-view-chip-background-color** - Specifies the background color of the component's `selectionMode` selection out of view chip.
*   **\--calcite-table-selection-out-of-view-chip-border-color** - Specifies the border color of the component's `selectionMode` selection out of view chip.
*   **\--calcite-table-selection-out-of-view-chip-corner-radius** - Specifies the corner radius of the component's `selectionMode` selection out of view chip.
*   **\--calcite-table-selection-out-of-view-chip-icon-color** - Specifies the icon color of the component's `selectionMode` selection out of view chip.
*   **\--calcite-table-selection-out-of-view-chip-shadow** - Specifies the shadow of the component's `selectionMode` selection out of view chip.
*   **\--calcite-table-selection-out-of-view-chip-text-color** - Specifies the text color of the component's `selectionMode` selection out of view chip.
*   **\--calcite-table-selection-dismiss-button-background-color-active** - Specifies the background color of the component's `selectionMode` selection dismiss chip when active.
*   **\--calcite-table-selection-dismiss-button-background-color-hover** - Specifies the background color of the component's `selectionMode` selection dismiss chip when hovered.
*   **\--calcite-table-selection-dismiss-button-background-color** - Specifies the background color of the component's `selectionMode` selection dismiss chip.
*   **\--calcite-table-selection-dismiss-button-border-color-active** - Specifies the border color of the component's `selectionMode` selection dismiss chip when active.
*   **\--calcite-table-selection-dismiss-button-border-color-hover** - Specifies the border color of the component's `selectionMode` selection dismiss chip when hovered.
*   **\--calcite-table-selection-dismiss-button-border-color** - Specifies the border color of the component's `selectionMode` selection dismiss chip.
*   **\--calcite-table-selection-dismiss-button-corner-radius** - Specifies the corner radius of the component's `selectionMode` selection dismiss chip.
*   **\--calcite-table-selection-dismiss-button-shadow** - Specifies the shadow of the component's `selectionMode` selection dismiss chip.
*   **\--calcite-table-selection-dismiss-button-text-color-active** - Specifies the text color of the component's `selectionMode` selection dismiss chip when active.
*   **\--calcite-table-selection-dismiss-button-text-color-hover** - Specifies the text color of the component's `selectionMode` selection dismiss chip when hovered.
*   **\--calcite-table-selection-dismiss-button-text-color** - Specifies the text color of the component's `selectionMode` selection dismiss chip.
*   **\--calcite-table-pagination-color** - Specifies the component's `pageSize` pagination item color.
*   **\--calcite-table-pagination-color-hover** - Specifies the component's `pageSize` pagination item color when hovered or selected.
*   **\--calcite-table-pagination-color-border-hover** - Specifies the component's `pageSize` pagination item bottom border color when hovered.
*   **\--calcite-table-pagination-color-border-active** - Specifies the component's `pageSize` pagination item bottom border color when selected.
*   **\--calcite-table-pagination-background-color** - Specifies the component's `pageSize` pagination item background color when active.
*   **\--calcite-table-pagination-icon-color-background-hover** - Specifies the component's `pageSize` pagination chevron item background color when hovered.

---

## calcite-table-cell

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding content, usually text content.

### CSS Properties

*   **\--calcite-table-cell-background** - \[Deprecated\] Use `--calcite-table-cell-background-color` instead. Specifies the component's background color.
*   **\--calcite-table-cell-background-color** - Specifies the component's background color.
*   **\--calcite-table-cell-border-color** - Specifies the component's border color.
*   **\--calcite-table-cell-text-color** - Specifies the component's text color.

---

## calcite-table-header

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### CSS Properties

*   **\--calcite-table-header-background** - \[Deprecated\] Use the `--calcite-table-header-background-color` property instead. Specifies the component's background color.
*   **\--calcite-table-header-background-color** - Specifies the component's background color.
*   **\--calcite-table-header-border-color** - Specifies the component's border color.
*   **\--calcite-table-header-heading-text-color** - Specifies the component's `heading` text color.
*   **\--calcite-table-header-description-text-color** - Specifies the component's `description` text color.

---

## calcite-table-row

### Events

*   **calciteTableRowSelect** - Fires when the selected state of the component changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding `calcite-table-cell` or `calcite-table-header` elements.

### CSS Properties

*   **\--calcite-table-row-background** - \[Deprecated\] Use `--calcite-table-row-background-color` instead. Specifies the background color of the component.
*   **\--calcite-table-row-background-color** - Specifies the background color of the component.
*   **\--calcite-table-row-background-color-striped** - The background color of the component's `striped` rows, when specified.
*   **\--calcite-table-row-background-color-selected** - The background color of the component's `selected` rows, when specified.
*   **\--calcite-table-row-accent-color-selected** - Specifies the selected accent color of the component.
*   **\--calcite-table-row-border-color** - Specifies the border color of the component.

---

## calcite-tabs

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding `calcite-tab`s.
*   **title-group** - A slot for adding a `calcite-tab-nav`.

### CSS Properties

*   **\--calcite-tab-background-color** - When `bordered`, specifies the component's background color.
*   **\--calcite-tab-border-color** - Specifies the component's border color.

---

## calcite-text-area

### Events

*   **calciteTextAreaChange** - Fires each time a new `value` is typed and committed.
*   **calciteTextAreaInput** - Fires each time a new `value` is typed.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `selectText(): Promise` - Selects the text of the component's `value` .
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding text.
*   **label-content** - A slot for rendering content next to the component's `labelText`.
*   **footer-start** - A slot for adding content to the start of the component's footer.
*   **footer-end** - A slot for adding content to the end of the component's footer.

### CSS Properties

*   **\--calcite-text-area-background-color** - Specifies the component's background color.
*   **\--calcite-text-area-border-color** - Specifies the component's text area border color.
*   **\--calcite-text-area-character-limit-text-color** - Specifies the color of the character limit text displayed in the footer of the component.
*   **\--calcite-text-area-divider-color** - Specifies the color of the divider between the text area and footer.
*   **\--calcite-text-area-font-size** - Specifies the font size of the text area and footer.
*   **\--calcite-text-area-max-height** - Specifies the component's text area maximum height.
*   **\--calcite-text-area-min-height** - Specifies the component's text area minimum height.
*   **\--calcite-text-area-max-width** - Specifies the component's text area maximum width.
*   **\--calcite-text-area-min-width** - Specifies the component's text area minimum width.
*   **\--calcite-text-area-text-color** - Specifies the component's text color.
*   **\--calcite-text-area-footer-border-color** - Specifies the footer's border color.
*   **\--calcite-text-area-corner-radius** - Specifies component's corner radius.
*   **\--calcite-text-area-shadow** - Specifies the component's shadow.
*   **\--calcite-text-area-footer-background-color** - Specifies the footer's background color.

---

## calcite-tile

### Events

*   **calciteTileSelect** - Fires when the selected state of the component changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   **content-top** - A slot for adding non-actionable elements above the component's content. Content slotted here will render in place of the `icon` property.
*   **content-bottom** - A slot for adding non-actionable elements below the component's content.
*   **content-start** - \[Deprecated\] use `content-top` slot instead. A slot for adding non-actionable elements before the component's content.
*   **content-end** - \[Deprecated\] use `content-bottom` slot instead. A slot for adding non-actionable elements after the component's content.

### CSS Properties

*   **\--calcite-tile-accent-color-press** - When the parent `calcite-tile-group` has a `selectionMode` that is not `"none"`, specifies the color of the component's selection elements, such as the radio, checkbox, and border.
*   **\--calcite-tile-background-color** - Specifies the component's background color.
*   **\--calcite-tile-border-color** - Specifies the component's border color.
*   **\--calcite-tile-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-tile-heading-text-color** - Specifies the component's `heading` text color.
*   **\--calcite-tile-link-color** - When `href` is present, specifies the component's link color.
*   **\--calcite-tile-shadow** - Specifies the shadow around the component.
*   **\--calcite-tile-text-color** - Specifies the component's `description` and `icon` text color, but not the `heading` text color.
*   **\--calcite-tile-link-text-color** - Specifies the component's link text color.

---

## calcite-tile-group

### Events

*   **calciteTileGroupSelect** - Fires when the component's selection changes.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding `calcite-tile` elements.

---

## calcite-tile-select

**Deprecated**: Use the `calcite-tile` component instead..

### Events

*   **calciteTileSelectChange** - Emits a custom change event.

For checkboxes it emits when checked or unchecked.

For radios it only emits when checked.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component.

### Slots

*   _default_ - A slot for adding custom content.

---

## calcite-tile-select-group

**Deprecated**: Use the `calcite-tile-group` component instead..

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding `calcite-tile-select` elements.

---

## calcite-time-picker

### Events

*   **calciteTimePickerChange** - Fires when a user changes the component's time

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `setFocus(options?: FocusOptions): Promise` - Sets focus on the component's first focusable element.

### CSS Properties

*   **\--calcite-time-picker-background-color** - Specifies the background color of the time picker.
*   **\--calcite-time-picker-border-color** - Specifies the border color of the time picker.
*   **\--calcite-time-picker-corner-radius** - Specifies the border radius of the time picker.
*   **\--calcite-time-picker-button-background-color-hover** - Specifies the button's background color when hovered or focused.
*   **\--calcite-time-picker-button-background-color-press** - Specifies the button's background color when active.
*   **\--calcite-time-picker-color** - Specifies the component's text color.
*   **\--calcite-time-picker-icon-color** - Specifies the component's icon color.
*   **\--calcite-time-picker-input-border-color-press** - Specifies the input's border color when active.
*   **\--calcite-time-picker-input-border-color-hover** - Specifies the input's border color when hovered.

---

## calcite-tip

**Deprecated**: Use the `calcite-card` , `calcite-notice` , `calcite-panel` , or `calcite-tile` component instead..

### Events

*   **calciteTipDismiss** - Emits when the component has been closed.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding text and a hyperlink.
*   **thumbnail** - A slot for adding an HTML image element.

---

## calcite-tip-group

**Deprecated**: Use the `calcite-carousel` and `calcite-carousel-item` components instead..

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding `calcite-tip`s.

---

## calcite-tip-manager

**Deprecated**: Use the `calcite-carousel` and `calcite-carousel-item` components instead.

---

### Events

*   **calciteTipManagerClose** - Emits when the component has been closed.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `nextTip(): Promise` - Selects the next `calcite-tip` to display.
*   `previousTip(): Promise` - Selects the previous `calcite-tip` to display.

### Slots

*   _default_ - A slot for adding `calcite-tip`s.

### CSS Properties

*   **\--calcite-tip-manager-height** - The maximum height of the component.
*   **\--calcite-tip-max-width** - The maximum width of a slotted `calcite-tip` within the component.

---

## calcite-tooltip

### Events

*   **calciteTooltipBeforeClose** - Fires when the component is requested to be closed and before the closing transition begins.
*   **calciteTooltipBeforeOpen** - Fires when the component is added to the DOM but not rendered, and before the opening transition begins.
*   **calciteTooltipClose** - Fires when the component is closed and animation is complete.
*   **calciteTooltipOpen** - Fires when the component is open and animation is complete.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.
*   `reposition(delayed?: boolean): Promise` - Updates the position of the component.

### Slots

*   _default_ - A slot for adding text.

### CSS Properties

*   **\--calcite-tooltip-background-color** - Specifies the component's background color.
*   **\--calcite-tooltip-border-color** - Specifies the component's border color.
*   **\--calcite-tooltip-corner-radius** - Specifies the component's corner radius.
*   **\--calcite-tooltip-max-size-x** - Specifies the component's maximum width.
*   **\--calcite-tooltip-text-color** - Specifies the component's text color.
*   **\--calcite-tooltip-z-index** - Specifies the z-index value for the component.

---

## calcite-tree

### Events

*   **calciteTreeSelect** - Fires when the user selects/deselects `calcite-tree-items`.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for `calcite-tree-item` elements.

---

## calcite-tree-item

### Events

*   **calciteTreeItemCollapse** - Fires when the component's content area is collapsed.
*   **calciteTreeItemExpand** - Fires when the component's content area is expanded.

### Methods

*   `componentOnReady(): Promise` - Create a promise that resolves once component is fully loaded.

### Slots

*   _default_ - A slot for adding text.
*   **children** - A slot for adding nested `calcite-tree` elements.
*   **actions-end** - A slot for adding actions to the end of the component. It is recommended to use two or fewer actions.

### CSS Properties

*   **\--calcite-tree-text-color** - Specifies the component's text color.
*   **\--calcite-tree-text-color-selected** - Specifies the component's text color when selected.
*   **\--calcite-tree-selected-icon-color** - Specifies the component's selection icon color.E