---
title: "Under development"
date: 2025-12-05
---

<html lang="en">
<head><meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>intro-and-eda</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<style type="text/css">
    pre { line-height: 125%; }
td.linenos .normal { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
span.linenos { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
td.linenos .special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
span.linenos.special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
.highlight .hll { background-color: var(--jp-cell-editor-active-background) }
.highlight { background: var(--jp-cell-editor-background); color: var(--jp-mirror-editor-variable-color) }
.highlight .c { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment */
.highlight .err { color: var(--jp-mirror-editor-error-color) } /* Error */
.highlight .k { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword */
.highlight .o { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator */
.highlight .p { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation */
.highlight .ch { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Multiline */
.highlight .cp { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Preproc */
.highlight .cpf { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Single */
.highlight .cs { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Special */
.highlight .kc { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Pseudo */
.highlight .kr { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Type */
.highlight .m { color: var(--jp-mirror-editor-number-color) } /* Literal.Number */
.highlight .s { color: var(--jp-mirror-editor-string-color) } /* Literal.String */
.highlight .ow { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator.Word */
.highlight .pm { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation.Marker */
.highlight .w { color: var(--jp-mirror-editor-variable-color) } /* Text.Whitespace */
.highlight .mb { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Bin */
.highlight .mf { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Float */
.highlight .mh { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Hex */
.highlight .mi { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer */
.highlight .mo { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Oct */
.highlight .sa { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Affix */
.highlight .sb { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Backtick */
.highlight .sc { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Char */
.highlight .dl { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Delimiter */
.highlight .sd { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Doc */
.highlight .s2 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Double */
.highlight .se { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Escape */
.highlight .sh { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Heredoc */
.highlight .si { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Interpol */
.highlight .sx { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Other */
.highlight .sr { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Regex */
.highlight .s1 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Single */
.highlight .ss { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Symbol */
.highlight .il { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer.Long */
  </style>
<style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
 * Mozilla scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */
[data-jp-theme-scrollbars='true'] {
  scrollbar-color: rgb(var(--jp-scrollbar-thumb-color))
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar. These selectors
 * will match lower in the tree, and so will override the above */
[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
}

/* tiny scrollbar */

.jp-scrollbar-tiny {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
  scrollbar-width: thin;
}

/* tiny scrollbar */

.jp-scrollbar-tiny::-webkit-scrollbar,
.jp-scrollbar-tiny::-webkit-scrollbar-corner {
  background-color: transparent;
  height: 4px;
  width: 4px;
}

.jp-scrollbar-tiny::-webkit-scrollbar-thumb {
  background: rgba(var(--jp-scrollbar-thumb-color), 0.5);
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:horizontal {
  border-left: 0 solid transparent;
  border-right: 0 solid transparent;
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:vertical {
  border-top: 0 solid transparent;
  border-bottom: 0 solid transparent;
}

/*
 * Lumino
 */

.lm-ScrollBar[data-orientation='horizontal'] {
  min-height: 16px;
  max-height: 16px;
  min-width: 45px;
  border-top: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] {
  min-width: 16px;
  max-width: 16px;
  min-height: 45px;
  border-left: 1px solid #a0a0a0;
}

.lm-ScrollBar-button {
  background-color: #f0f0f0;
  background-position: center center;
  min-height: 15px;
  max-height: 15px;
  min-width: 15px;
  max-width: 15px;
}

.lm-ScrollBar-button:hover {
  background-color: #dadada;
}

.lm-ScrollBar-button.lm-mod-active {
  background-color: #cdcdcd;
}

.lm-ScrollBar-track {
  background: #f0f0f0;
}

.lm-ScrollBar-thumb {
  background: #cdcdcd;
}

.lm-ScrollBar-thumb:hover {
  background: #bababa;
}

.lm-ScrollBar-thumb.lm-mod-active {
  background: #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal'] .lm-ScrollBar-thumb {
  height: 100%;
  min-width: 15px;
  border-left: 1px solid #a0a0a0;
  border-right: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] .lm-ScrollBar-thumb {
  width: 100%;
  min-height: 15px;
  border-top: 1px solid #a0a0a0;
  border-bottom: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-left);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-right);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-up);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-down);
  background-size: 17px;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-Widget {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
}

.lm-Widget.lm-mod-hidden {
  display: none !important;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.lm-AccordionPanel[data-orientation='horizontal'] > .lm-AccordionPanel-title {
  /* Title is rotated for horizontal accordion panel using CSS */
  display: block;
  transform-origin: top left;
  transform: rotate(-90deg) translate(-100%);
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-CommandPalette {
  display: flex;
  flex-direction: column;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-CommandPalette-search {
  flex: 0 0 auto;
}

.lm-CommandPalette-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  min-height: 0;
  overflow: auto;
  list-style-type: none;
}

.lm-CommandPalette-header {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.lm-CommandPalette-item {
  display: flex;
  flex-direction: row;
}

.lm-CommandPalette-itemIcon {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemContent {
  flex: 1 1 auto;
  overflow: hidden;
}

.lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemLabel {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.lm-close-icon {
  border: 1px solid transparent;
  background-color: transparent;
  position: absolute;
  z-index: 1;
  right: 3%;
  top: 0;
  bottom: 0;
  margin: auto;
  padding: 7px 0;
  display: none;
  vertical-align: middle;
  outline: 0;
  cursor: pointer;
}
.lm-close-icon:after {
  content: 'X';
  display: block;
  width: 15px;
  height: 15px;
  text-align: center;
  color: #000;
  font-weight: normal;
  font-size: 12px;
  cursor: pointer;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-DockPanel {
  z-index: 0;
}

.lm-DockPanel-widget {
  z-index: 0;
}

.lm-DockPanel-tabBar {
  z-index: 1;
}

.lm-DockPanel-handle {
  z-index: 2;
}

.lm-DockPanel-handle.lm-mod-hidden {
  display: none !important;
}

.lm-DockPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}

.lm-DockPanel-handle[data-orientation='horizontal'] {
  cursor: ew-resize;
}

.lm-DockPanel-handle[data-orientation='vertical'] {
  cursor: ns-resize;
}

.lm-DockPanel-handle[data-orientation='horizontal']:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}

.lm-DockPanel-handle[data-orientation='vertical']:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}

.lm-DockPanel-overlay {
  z-index: 3;
  box-sizing: border-box;
  pointer-events: none;
}

.lm-DockPanel-overlay.lm-mod-hidden {
  display: none !important;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-Menu {
  z-index: 10000;
  position: absolute;
  white-space: nowrap;
  overflow-x: hidden;
  overflow-y: auto;
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-Menu-content {
  margin: 0;
  padding: 0;
  display: table;
  list-style-type: none;
}

.lm-Menu-item {
  display: table-row;
}

.lm-Menu-item.lm-mod-hidden,
.lm-Menu-item.lm-mod-collapsed {
  display: none !important;
}

.lm-Menu-itemIcon,
.lm-Menu-itemSubmenuIcon {
  display: table-cell;
  text-align: center;
}

.lm-Menu-itemLabel {
  display: table-cell;
  text-align: left;
}

.lm-Menu-itemShortcut {
  display: table-cell;
  text-align: right;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-MenuBar {
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-MenuBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: row;
  list-style-type: none;
}

.lm-MenuBar-item {
  box-sizing: border-box;
}

.lm-MenuBar-itemIcon,
.lm-MenuBar-itemLabel {
  display: inline-block;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-ScrollBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-ScrollBar[data-orientation='horizontal'] {
  flex-direction: row;
}

.lm-ScrollBar[data-orientation='vertical'] {
  flex-direction: column;
}

.lm-ScrollBar-button {
  box-sizing: border-box;
  flex: 0 0 auto;
}

.lm-ScrollBar-track {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  flex: 1 1 auto;
}

.lm-ScrollBar-thumb {
  box-sizing: border-box;
  position: absolute;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-SplitPanel-child {
  z-index: 0;
}

.lm-SplitPanel-handle {
  z-index: 1;
}

.lm-SplitPanel-handle.lm-mod-hidden {
  display: none !important;
}

.lm-SplitPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}

.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle {
  cursor: ew-resize;
}

.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle {
  cursor: ns-resize;
}

.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}

.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-TabBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-TabBar[data-orientation='horizontal'] {
  flex-direction: row;
  align-items: flex-end;
}

.lm-TabBar[data-orientation='vertical'] {
  flex-direction: column;
  align-items: flex-end;
}

.lm-TabBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex: 1 1 auto;
  list-style-type: none;
}

.lm-TabBar[data-orientation='horizontal'] > .lm-TabBar-content {
  flex-direction: row;
}

.lm-TabBar[data-orientation='vertical'] > .lm-TabBar-content {
  flex-direction: column;
}

.lm-TabBar-tab {
  display: flex;
  flex-direction: row;
  box-sizing: border-box;
  overflow: hidden;
  touch-action: none; /* Disable native Drag/Drop */
}

.lm-TabBar-tabIcon,
.lm-TabBar-tabCloseIcon {
  flex: 0 0 auto;
}

.lm-TabBar-tabLabel {
  flex: 1 1 auto;
  overflow: hidden;
  white-space: nowrap;
}

.lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing: border-box;
}

.lm-TabBar-tab.lm-mod-hidden {
  display: none !important;
}

.lm-TabBar-addButton.lm-mod-hidden {
  display: none !important;
}

.lm-TabBar.lm-mod-dragging .lm-TabBar-tab {
  position: relative;
}

.lm-TabBar.lm-mod-dragging[data-orientation='horizontal'] .lm-TabBar-tab {
  left: 0;
  transition: left 150ms ease;
}

.lm-TabBar.lm-mod-dragging[data-orientation='vertical'] .lm-TabBar-tab {
  top: 0;
  transition: top 150ms ease;
}

.lm-TabBar.lm-mod-dragging .lm-TabBar-tab.lm-mod-dragging {
  transition: none;
}

.lm-TabBar-tabLabel .lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing: border-box;
  background: inherit;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-TabPanel-tabBar {
  z-index: 1;
}

.lm-TabPanel-stackedPanel {
  z-index: 0;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapse {
  display: flex;
  flex-direction: column;
  align-items: stretch;
}

.jp-Collapse-header {
  padding: 1px 12px;
  background-color: var(--jp-layout-color1);
  border-bottom: solid var(--jp-border-width) var(--jp-border-color2);
  color: var(--jp-ui-font-color1);
  cursor: pointer;
  display: flex;
  align-items: center;
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  text-transform: uppercase;
  user-select: none;
}

.jp-Collapser-icon {
  height: 16px;
}

.jp-Collapse-header-collapsed .jp-Collapser-icon {
  transform: rotate(-90deg);
  margin: auto 0;
}

.jp-Collapser-title {
  line-height: 25px;
}

.jp-Collapse-contents {
  padding: 0 12px;
  background-color: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  overflow: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensureUiComponents() in @jupyterlab/buildutils */

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

/* Icons urls */

:root {
  --jp-icon-add-above: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGcgY2xpcC1wYXRoPSJ1cmwoI2NsaXAwXzEzN18xOTQ5MikiPgo8cGF0aCBjbGFzcz0ianAtaWNvbjMiIGQ9Ik00Ljc1IDQuOTMwNjZINi42MjVWNi44MDU2NkM2LjYyNSA3LjAxMTkxIDYuNzkzNzUgNy4xODA2NiA3IDcuMTgwNjZDNy4yMDYyNSA3LjE4MDY2IDcuMzc1IDcuMDExOTEgNy4zNzUgNi44MDU2NlY0LjkzMDY2SDkuMjVDOS40NTYyNSA0LjkzMDY2IDkuNjI1IDQuNzYxOTEgOS42MjUgNC41NTU2NkM5LjYyNSA0LjM0OTQxIDkuNDU2MjUgNC4xODA2NiA5LjI1IDQuMTgwNjZINy4zNzVWMi4zMDU2NkM3LjM3NSAyLjA5OTQxIDcuMjA2MjUgMS45MzA2NiA3IDEuOTMwNjZDNi43OTM3NSAxLjkzMDY2IDYuNjI1IDIuMDk5NDEgNi42MjUgMi4zMDU2NlY0LjE4MDY2SDQuNzVDNC41NDM3NSA0LjE4MDY2IDQuMzc1IDQuMzQ5NDEgNC4zNzUgNC41NTU2NkM0LjM3NSA0Ljc2MTkxIDQuNTQzNzUgNC45MzA2NiA0Ljc1IDQuOTMwNjZaIiBmaWxsPSIjNjE2MTYxIiBzdHJva2U9IiM2MTYxNjEiIHN0cm9rZS13aWR0aD0iMC43Ii8+CjwvZz4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGNsaXAtcnVsZT0iZXZlbm9kZCIgZD0iTTExLjUgOS41VjExLjVMMi41IDExLjVWOS41TDExLjUgOS41Wk0xMiA4QzEyLjU1MjMgOCAxMyA4LjQ0NzcyIDEzIDlWMTJDMTMgMTIuNTUyMyAxMi41NTIzIDEzIDEyIDEzTDIgMTNDMS40NDc3MiAxMyAxIDEyLjU1MjMgMSAxMlY5QzEgOC40NDc3MiAxLjQ0NzcxIDggMiA4TDEyIDhaIiBmaWxsPSIjNjE2MTYxIi8+CjxkZWZzPgo8Y2xpcFBhdGggaWQ9ImNsaXAwXzEzN18xOTQ5MiI+CjxyZWN0IGNsYXNzPSJqcC1pY29uMyIgd2lkdGg9IjYiIGhlaWdodD0iNiIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0ibWF0cml4KC0xIDAgMCAxIDEwIDEuNTU1NjYpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==);
  --jp-icon-add-below: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGcgY2xpcC1wYXRoPSJ1cmwoI2NsaXAwXzEzN18xOTQ5OCkiPgo8cGF0aCBjbGFzcz0ianAtaWNvbjMiIGQ9Ik05LjI1IDEwLjA2OTNMNy4zNzUgMTAuMDY5M0w3LjM3NSA4LjE5NDM0QzcuMzc1IDcuOTg4MDkgNy4yMDYyNSA3LjgxOTM0IDcgNy44MTkzNEM2Ljc5Mzc1IDcuODE5MzQgNi42MjUgNy45ODgwOSA2LjYyNSA4LjE5NDM0TDYuNjI1IDEwLjA2OTNMNC43NSAxMC4wNjkzQzQuNTQzNzUgMTAuMDY5MyA0LjM3NSAxMC4yMzgxIDQuMzc1IDEwLjQ0NDNDNC4zNzUgMTAuNjUwNiA0LjU0Mzc1IDEwLjgxOTMgNC43NSAxMC44MTkzTDYuNjI1IDEwLjgxOTNMNi42MjUgMTIuNjk0M0M2LjYyNSAxMi45MDA2IDYuNzkzNzUgMTMuMDY5MyA3IDEzLjA2OTNDNy4yMDYyNSAxMy4wNjkzIDcuMzc1IDEyLjkwMDYgNy4zNzUgMTIuNjk0M0w3LjM3NSAxMC44MTkzTDkuMjUgMTAuODE5M0M5LjQ1NjI1IDEwLjgxOTMgOS42MjUgMTAuNjUwNiA5LjYyNSAxMC40NDQzQzkuNjI1IDEwLjIzODEgOS40NTYyNSAxMC4wNjkzIDkuMjUgMTAuMDY5M1oiIGZpbGw9IiM2MTYxNjEiIHN0cm9rZT0iIzYxNjE2MSIgc3Ryb2tlLXdpZHRoPSIwLjciLz4KPC9nPgo8cGF0aCBjbGFzcz0ianAtaWNvbjMiIGZpbGwtcnVsZT0iZXZlbm9kZCIgY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNMi41IDUuNUwyLjUgMy41TDExLjUgMy41TDExLjUgNS41TDIuNSA1LjVaTTIgN0MxLjQ0NzcyIDcgMSA2LjU1MjI4IDEgNkwxIDNDMSAyLjQ0NzcyIDEuNDQ3NzIgMiAyIDJMMTIgMkMxMi41NTIzIDIgMTMgMi40NDc3MiAxMyAzTDEzIDZDMTMgNi41NTIyOSAxMi41NTIzIDcgMTIgN0wyIDdaIiBmaWxsPSIjNjE2MTYxIi8+CjxkZWZzPgo8Y2xpcFBhdGggaWQ9ImNsaXAwXzEzN18xOTQ5OCI+CjxyZWN0IGNsYXNzPSJqcC1pY29uMyIgd2lkdGg9IjYiIGhlaWdodD0iNiIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0ibWF0cml4KDEgMS43NDg0NmUtMDcgMS43NDg0NmUtMDcgLTEgNCAxMy40NDQzKSIvPgo8L2NsaXBQYXRoPgo8L2RlZnM+Cjwvc3ZnPgo=);
  --jp-icon-add: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDEzaC02djZoLTJ2LTZINXYtMmg2VjVoMnY2aDZ2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-bell: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE2IDE2IiB2ZXJzaW9uPSIxLjEiPgogICA8cGF0aCBjbGFzcz0ianAtaWNvbjIganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMzMzMzMzIgogICAgICBkPSJtOCAwLjI5Yy0xLjQgMC0yLjcgMC43My0zLjYgMS44LTEuMiAxLjUtMS40IDMuNC0xLjUgNS4yLTAuMTggMi4yLTAuNDQgNC0yLjMgNS4zbDAuMjggMS4zaDVjMC4wMjYgMC42NiAwLjMyIDEuMSAwLjcxIDEuNSAwLjg0IDAuNjEgMiAwLjYxIDIuOCAwIDAuNTItMC40IDAuNi0xIDAuNzEtMS41aDVsMC4yOC0xLjNjLTEuOS0wLjk3LTIuMi0zLjMtMi4zLTUuMy0wLjEzLTEuOC0wLjI2LTMuNy0xLjUtNS4yLTAuODUtMS0yLjItMS44LTMuNi0xLjh6bTAgMS40YzAuODggMCAxLjkgMC41NSAyLjUgMS4zIDAuODggMS4xIDEuMSAyLjcgMS4yIDQuNCAwLjEzIDEuNyAwLjIzIDMuNiAxLjMgNS4yaC0xMGMxLjEtMS42IDEuMi0zLjQgMS4zLTUuMiAwLjEzLTEuNyAwLjMtMy4zIDEuMi00LjQgMC41OS0wLjcyIDEuNi0xLjMgMi41LTEuM3ptLTAuNzQgMTJoMS41Yy0wLjAwMTUgMC4yOCAwLjAxNSAwLjc5LTAuNzQgMC43OS0wLjczIDAuMDAxNi0wLjcyLTAuNTMtMC43NC0wLjc5eiIgLz4KPC9zdmc+Cg==);
  --jp-icon-bug-dot: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiPgogICAgICAgIDxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNMTcuMTkgOEgyMFYxMEgxNy45MUMxNy45NiAxMC4zMyAxOCAxMC42NiAxOCAxMVYxMkgyMFYxNEgxOC41SDE4VjE0LjAyNzVDMTUuNzUgMTQuMjc2MiAxNCAxNi4xODM3IDE0IDE4LjVDMTQgMTkuMjA4IDE0LjE2MzUgMTkuODc3OSAxNC40NTQ5IDIwLjQ3MzlDMTMuNzA2MyAyMC44MTE3IDEyLjg3NTcgMjEgMTIgMjFDOS43OCAyMSA3Ljg1IDE5Ljc5IDYuODEgMThINFYxNkg2LjA5QzYuMDQgMTUuNjcgNiAxNS4zNCA2IDE1VjE0SDRWMTJINlYxMUM2IDEwLjY2IDYuMDQgMTAuMzMgNi4wOSAxMEg0VjhINi44MUM3LjI2IDcuMjIgNy44OCA2LjU1IDguNjIgNi4wNEw3IDQuNDFMOC40MSAzTDEwLjU5IDUuMTdDMTEuMDQgNS4wNiAxMS41MSA1IDEyIDVDMTIuNDkgNSAxMi45NiA1LjA2IDEzLjQyIDUuMTdMMTUuNTkgM0wxNyA0LjQxTDE1LjM3IDYuMDRDMTYuMTIgNi41NSAxNi43NCA3LjIyIDE3LjE5IDhaTTEwIDE2SDE0VjE0SDEwVjE2Wk0xMCAxMkgxNFYxMEgxMFYxMloiIGZpbGw9IiM2MTYxNjEiLz4KICAgICAgICA8cGF0aCBkPSJNMjIgMTguNUMyMiAyMC40MzMgMjAuNDMzIDIyIDE4LjUgMjJDMTYuNTY3IDIyIDE1IDIwLjQzMyAxNSAxOC41QzE1IDE2LjU2NyAxNi41NjcgMTUgMTguNSAxNUMyMC40MzMgMTUgMjIgMTYuNTY3IDIyIDE4LjVaIiBmaWxsPSIjNjE2MTYxIi8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-bug: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0yMCA4aC0yLjgxYy0uNDUtLjc4LTEuMDctMS40NS0xLjgyLTEuOTZMMTcgNC40MSAxNS41OSAzbC0yLjE3IDIuMTdDMTIuOTYgNS4wNiAxMi40OSA1IDEyIDVjLS40OSAwLS45Ni4wNi0xLjQxLjE3TDguNDEgMyA3IDQuNDFsMS42MiAxLjYzQzcuODggNi41NSA3LjI2IDcuMjIgNi44MSA4SDR2MmgyLjA5Yy0uMDUuMzMtLjA5LjY2LS4wOSAxdjFINHYyaDJ2MWMwIC4zNC4wNC42Ny4wOSAxSDR2MmgyLjgxYzEuMDQgMS43OSAyLjk3IDMgNS4xOSAzczQuMTUtMS4yMSA1LjE5LTNIMjB2LTJoLTIuMDljLjA1LS4zMy4wOS0uNjYuMDktMXYtMWgydi0yaC0ydi0xYzAtLjM0LS4wNC0uNjctLjA5LTFIMjBWOHptLTYgOGgtNHYtMmg0djJ6bTAtNGgtNHYtMmg0djJ6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-build: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE0LjkgMTcuNDVDMTYuMjUgMTcuNDUgMTcuMzUgMTYuMzUgMTcuMzUgMTVDMTcuMzUgMTMuNjUgMTYuMjUgMTIuNTUgMTQuOSAxMi41NUMxMy41NCAxMi41NSAxMi40NSAxMy42NSAxMi40NSAxNUMxMi40NSAxNi4zNSAxMy41NCAxNy40NSAxNC45IDE3LjQ1Wk0yMC4xIDE1LjY4TDIxLjU4IDE2Ljg0QzIxLjcxIDE2Ljk1IDIxLjc1IDE3LjEzIDIxLjY2IDE3LjI5TDIwLjI2IDE5LjcxQzIwLjE3IDE5Ljg2IDIwIDE5LjkyIDE5LjgzIDE5Ljg2TDE4LjA5IDE5LjE2QzE3LjczIDE5LjQ0IDE3LjMzIDE5LjY3IDE2LjkxIDE5Ljg1TDE2LjY0IDIxLjdDMTYuNjIgMjEuODcgMTYuNDcgMjIgMTYuMyAyMkgxMy41QzEzLjMyIDIyIDEzLjE4IDIxLjg3IDEzLjE1IDIxLjdMMTIuODkgMTkuODVDMTIuNDYgMTkuNjcgMTIuMDcgMTkuNDQgMTEuNzEgMTkuMTZMOS45NjAwMiAxOS44NkM5LjgxMDAyIDE5LjkyIDkuNjIwMDIgMTkuODYgOS41NDAwMiAxOS43MUw4LjE0MDAyIDE3LjI5QzguMDUwMDIgMTcuMTMgOC4wOTAwMiAxNi45NSA4LjIyMDAyIDE2Ljg0TDkuNzAwMDIgMTUuNjhMOS42NTAwMSAxNUw5LjcwMDAyIDE0LjMxTDguMjIwMDIgMTMuMTZDOC4wOTAwMiAxMy4wNSA4LjA1MDAyIDEyLjg2IDguMTQwMDIgMTIuNzFMOS41NDAwMiAxMC4yOUM5LjYyMDAyIDEwLjEzIDkuODEwMDIgMTAuMDcgOS45NjAwMiAxMC4xM0wxMS43MSAxMC44NEMxMi4wNyAxMC41NiAxMi40NiAxMC4zMiAxMi44OSAxMC4xNUwxMy4xNSA4LjI4OTk4QzEzLjE4IDguMTI5OTggMTMuMzIgNy45OTk5OCAxMy41IDcuOTk5OThIMTYuM0MxNi40NyA3Ljk5OTk4IDE2LjYyIDguMTI5OTggMTYuNjQgOC4yODk5OEwxNi45MSAxMC4xNUMxNy4zMyAxMC4zMiAxNy43MyAxMC41NiAxOC4wOSAxMC44NEwxOS44MyAxMC4xM0MyMCAxMC4wNyAyMC4xNyAxMC4xMyAyMC4yNiAxMC4yOUwyMS42NiAxMi43MUMyMS43NSAxMi44NiAyMS43MSAxMy4wNSAyMS41OCAxMy4xNkwyMC4xIDE0LjMxTDIwLjE1IDE1TDIwLjEgMTUuNjhaIi8+CiAgICA8cGF0aCBkPSJNNy4zMjk2NiA3LjQ0NDU0QzguMDgzMSA3LjAwOTU0IDguMzM5MzIgNi4wNTMzMiA3LjkwNDMyIDUuMjk5ODhDNy40NjkzMiA0LjU0NjQzIDYuNTA4MSA0LjI4MTU2IDUuNzU0NjYgNC43MTY1NkM1LjM5MTc2IDQuOTI2MDggNS4xMjY5NSA1LjI3MTE4IDUuMDE4NDkgNS42NzU5NEM0LjkxMDA0IDYuMDgwNzEgNC45NjY4MiA2LjUxMTk4IDUuMTc2MzQgNi44NzQ4OEM1LjYxMTM0IDcuNjI4MzIgNi41NzYyMiA3Ljg3OTU0IDcuMzI5NjYgNy40NDQ1NFpNOS42NTcxOCA0Ljc5NTkzTDEwLjg2NzIgNC45NTE3OUMxMC45NjI4IDQuOTc3NDEgMTEuMDQwMiA1LjA3MTMzIDExLjAzODIgNS4xODc5M0wxMS4wMzg4IDYuOTg4OTNDMTEuMDQ1NSA3LjEwMDU0IDEwLjk2MTYgNy4xOTUxOCAxMC44NTUgNy4yMTA1NEw5LjY2MDAxIDcuMzgwODNMOS4yMzkxNSA4LjEzMTg4TDkuNjY5NjEgOS4yNTc0NUM5LjcwNzI5IDkuMzYyNzEgOS42NjkzNCA5LjQ3Njk5IDkuNTc0MDggOS41MzE5OUw4LjAxNTIzIDEwLjQzMkM3LjkxMTMxIDEwLjQ5MiA3Ljc5MzM3IDEwLjQ2NzcgNy43MjEwNSAxMC4zODI0TDYuOTg3NDggOS40MzE4OEw2LjEwOTMxIDkuNDMwODNMNS4zNDcwNCAxMC4zOTA1QzUuMjg5MDkgMTAuNDcwMiA1LjE3MzgzIDEwLjQ5MDUgNS4wNzE4NyAxMC40MzM5TDMuNTEyNDUgOS41MzI5M0MzLjQxMDQ5IDkuNDc2MzMgMy4zNzY0NyA5LjM1NzQxIDMuNDEwNzUgOS4yNTY3OUwzLjg2MzQ3IDguMTQwOTNMMy42MTc0OSA3Ljc3NDg4TDMuNDIzNDcgNy4zNzg4M0wyLjIzMDc1IDcuMjEyOTdDMi4xMjY0NyA3LjE5MjM1IDIuMDQwNDkgNy4xMDM0MiAyLjA0MjQ1IDYuOTg2ODJMMi4wNDE4NyA1LjE4NTgyQzIuMDQzODMgNS4wNjkyMiAyLjExOTA5IDQuOTc5NTggMi4yMTcwNCA0Ljk2OTIyTDMuNDIwNjUgNC43OTM5M0wzLjg2NzQ5IDQuMDI3ODhMMy40MTEwNSAyLjkxNzMxQzMuMzczMzcgMi44MTIwNCAzLjQxMTMxIDIuNjk3NzYgMy41MTUyMyAyLjYzNzc2TDUuMDc0MDggMS43Mzc3NkM1LjE2OTM0IDEuNjgyNzYgNS4yODcyOSAxLjcwNzA0IDUuMzU5NjEgMS43OTIzMUw2LjExOTE1IDIuNzI3ODhMNi45ODAwMSAyLjczODkzTDcuNzI0OTYgMS43ODkyMkM3Ljc5MTU2IDEuNzA0NTggNy45MTU0OCAxLjY3OTIyIDguMDA4NzkgMS43NDA4Mkw5LjU2ODIxIDIuNjQxODJDOS42NzAxNyAyLjY5ODQyIDkuNzEyODUgMi44MTIzNCA5LjY4NzIzIDIuOTA3OTdMOS4yMTcxOCA0LjAzMzgzTDkuNDYzMTYgNC4zOTk4OEw5LjY1NzE4IDQuNzk1OTNaIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iOS45LDEzLjYgMy42LDcuNCA0LjQsNi42IDkuOSwxMi4yIDE1LjQsNi43IDE2LjEsNy40ICIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNS45TDksOS43bDMuOC0zLjhsMS4yLDEuMmwtNC45LDVsLTQuOS01TDUuMiw1Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNy41TDksMTEuMmwzLjgtMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-left: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik0xMC44LDEyLjhMNy4xLDlsMy44LTMuOGwwLDcuNkgxMC44eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-right: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik03LjIsNS4yTDEwLjksOWwtMy44LDMuOFY1LjJINy4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-up-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iMTUuNCwxMy4zIDkuOSw3LjcgNC40LDEzLjIgMy42LDEyLjUgOS45LDYuMyAxNi4xLDEyLjYgIi8+Cgk8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-up: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik01LjIsMTAuNUw5LDYuOGwzLjgsMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-case-sensitive: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWFjY2VudDIiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTcuNiw4aDAuOWwzLjUsOGgtMS4xTDEwLDE0SDZsLTAuOSwySDRMNy42LDh6IE04LDkuMUw2LjQsMTNoMy4yTDgsOS4xeiIvPgogICAgPHBhdGggZD0iTTE2LjYsOS44Yy0wLjIsMC4xLTAuNCwwLjEtMC43LDAuMWMtMC4yLDAtMC40LTAuMS0wLjYtMC4yYy0wLjEtMC4xLTAuMi0wLjQtMC4yLTAuNyBjLTAuMywwLjMtMC42LDAuNS0wLjksMC43Yy0wLjMsMC4xLTAuNywwLjItMS4xLDAuMmMtMC4zLDAtMC41LDAtMC43LTAuMWMtMC4yLTAuMS0wLjQtMC4yLTAuNi0wLjNjLTAuMi0wLjEtMC4zLTAuMy0wLjQtMC41IGMtMC4xLTAuMi0wLjEtMC40LTAuMS0wLjdjMC0wLjMsMC4xLTAuNiwwLjItMC44YzAuMS0wLjIsMC4zLTAuNCwwLjQtMC41QzEyLDcsMTIuMiw2LjksMTIuNSw2LjhjMC4yLTAuMSwwLjUtMC4xLDAuNy0wLjIgYzAuMy0wLjEsMC41LTAuMSwwLjctMC4xYzAuMiwwLDAuNC0wLjEsMC42LTAuMWMwLjIsMCwwLjMtMC4xLDAuNC0wLjJjMC4xLTAuMSwwLjItMC4yLDAuMi0wLjRjMC0xLTEuMS0xLTEuMy0xIGMtMC40LDAtMS40LDAtMS40LDEuMmgtMC45YzAtMC40LDAuMS0wLjcsMC4yLTFjMC4xLTAuMiwwLjMtMC40LDAuNS0wLjZjMC4yLTAuMiwwLjUtMC4zLDAuOC0wLjNDMTMuMyw0LDEzLjYsNCwxMy45LDQgYzAuMywwLDAuNSwwLDAuOCwwLjFjMC4zLDAsMC41LDAuMSwwLjcsMC4yYzAuMiwwLjEsMC40LDAuMywwLjUsMC41QzE2LDUsMTYsNS4yLDE2LDUuNnYyLjljMCwwLjIsMCwwLjQsMCwwLjUgYzAsMC4xLDAuMSwwLjIsMC4zLDAuMmMwLjEsMCwwLjIsMCwwLjMsMFY5Ljh6IE0xNS4yLDYuOWMtMS4yLDAuNi0zLjEsMC4yLTMuMSwxLjRjMCwxLjQsMy4xLDEsMy4xLTAuNVY2Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik05IDE2LjE3TDQuODMgMTJsLTEuNDIgMS40MUw5IDE5IDIxIDdsLTEuNDEtMS40MXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-circle-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDJDNi40NyAyIDIgNi40NyAyIDEyczQuNDcgMTAgMTAgMTAgMTAtNC40NyAxMC0xMFMxNy41MyAyIDEyIDJ6bTAgMThjLTQuNDEgMC04LTMuNTktOC04czMuNTktOCA4LTggOCAzLjU5IDggOC0zLjU5IDgtOCA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-circle: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iOSIgY3k9IjkiIHI9IjgiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-clear: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8bWFzayBpZD0iZG9udXRIb2xlIj4KICAgIDxyZWN0IHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgZmlsbD0id2hpdGUiIC8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI4IiBmaWxsPSJibGFjayIvPgogIDwvbWFzaz4KCiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxyZWN0IGhlaWdodD0iMTgiIHdpZHRoPSIyIiB4PSIxMSIgeT0iMyIgdHJhbnNmb3JtPSJyb3RhdGUoMzE1LCAxMiwgMTIpIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIxMCIgbWFzaz0idXJsKCNkb251dEhvbGUpIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-close: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1ub25lIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIGpwLWljb24zLWhvdmVyIiBmaWxsPSJub25lIj4KICAgIDxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjExIi8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIGpwLWljb24tYWNjZW50Mi1ob3ZlciIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMTkgNi40MUwxNy41OSA1IDEyIDEwLjU5IDYuNDEgNSA1IDYuNDEgMTAuNTkgMTIgNSAxNy41OSA2LjQxIDE5IDEyIDEzLjQxIDE3LjU5IDE5IDE5IDE3LjU5IDEzLjQxIDEyeiIvPgogIDwvZz4KCiAgPGcgY2xhc3M9ImpwLWljb24tbm9uZSBqcC1pY29uLWJ1c3kiIGZpbGw9Im5vbmUiPgogICAgPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-code-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBzaGFwZS1yZW5kZXJpbmc9Imdlb21ldHJpY1ByZWNpc2lvbiI+CiAgICA8cGF0aCBkPSJNNi41OSwzLjQxTDIsOEw2LjU5LDEyLjZMOCwxMS4xOEw0LjgyLDhMOCw0LjgyTDYuNTksMy40MU0xMi40MSwzLjQxTDExLDQuODJMMTQuMTgsOEwxMSwxMS4xOEwxMi40MSwxMi42TDE3LDhMMTIuNDEsMy40MU0yMS41OSwxMS41OUwxMy41LDE5LjY4TDkuODMsMTZMOC40MiwxNy40MUwxMy41LDIyLjVMMjMsMTNMMjEuNTksMTEuNTlaIiAvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-code: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTExLjQgMTguNkw2LjggMTRMMTEuNCA5LjRMMTAgOEw0IDE0TDEwIDIwTDExLjQgMTguNlpNMTYuNiAxOC42TDIxLjIgMTRMMTYuNiA5LjRMMTggOEwyNCAxNEwxOCAyMEwxNi42IDE4LjZWMTguNloiLz4KCTwvZz4KPC9zdmc+Cg==);
  --jp-icon-collapse-all: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTggMmMxIDAgMTEgMCAxMiAwczIgMSAyIDJjMCAxIDAgMTEgMCAxMnMwIDItMiAyQzIwIDE0IDIwIDQgMjAgNFMxMCA0IDYgNGMwLTIgMS0yIDItMnoiIC8+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTE4IDhjMC0xLTEtMi0yLTJTNSA2IDQgNnMtMiAxLTIgMmMwIDEgMCAxMSAwIDEyczEgMiAyIDJjMSAwIDExIDAgMTIgMHMyLTEgMi0yYzAtMSAwLTExIDAtMTJ6bS0yIDB2MTJINFY4eiIgLz4KICAgICAgICA8cGF0aCBkPSJNNiAxM3YyaDh2LTJ6IiAvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-console: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwMCAyMDAiPgogIDxnIGNsYXNzPSJqcC1jb25zb2xlLWljb24tYmFja2dyb3VuZC1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMjg4RDEiPgogICAgPHBhdGggZD0iTTIwIDE5LjhoMTYwdjE1OS45SDIweiIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtY29uc29sZS1pY29uLWNvbG9yIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIiBmaWxsPSIjZmZmIj4KICAgIDxwYXRoIGQ9Ik0xMDUgMTI3LjNoNDB2MTIuOGgtNDB6TTUxLjEgNzdMNzQgOTkuOWwtMjMuMyAyMy4zIDEwLjUgMTAuNSAyMy4zLTIzLjNMOTUgOTkuOSA4NC41IDg5LjQgNjEuNiA2Ni41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-copy: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTExLjksMUgzLjJDMi40LDEsMS43LDEuNywxLjcsMi41djEwLjJoMS41VjIuNWg4LjdWMXogTTE0LjEsMy45aC04Yy0wLjgsMC0xLjUsMC43LTEuNSwxLjV2MTAuMmMwLDAuOCwwLjcsMS41LDEuNSwxLjVoOCBjMC44LDAsMS41LTAuNywxLjUtMS41VjUuNEMxNS41LDQuNiwxNC45LDMuOSwxNC4xLDMuOXogTTE0LjEsMTUuNWgtOFY1LjRoOFYxNS41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-copyright: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDI0IDI0IiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCI+CiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0xMS44OCw5LjE0YzEuMjgsMC4wNiwxLjYxLDEuMTUsMS42MywxLjY2aDEuNzljLTAuMDgtMS45OC0xLjQ5LTMuMTktMy40NS0zLjE5QzkuNjQsNy42MSw4LDksOCwxMi4xNCBjMCwxLjk0LDAuOTMsNC4yNCwzLjg0LDQuMjRjMi4yMiwwLDMuNDEtMS42NSwzLjQ0LTIuOTVoLTEuNzljLTAuMDMsMC41OS0wLjQ1LDEuMzgtMS42MywxLjQ0QzEwLjU1LDE0LjgzLDEwLDEzLjgxLDEwLDEyLjE0IEMxMCw5LjI1LDExLjI4LDkuMTYsMTEuODgsOS4xNHogTTEyLDJDNi40OCwyLDIsNi40OCwyLDEyczQuNDgsMTAsMTAsMTBzMTAtNC40OCwxMC0xMFMxNy41MiwyLDEyLDJ6IE0xMiwyMGMtNC40MSwwLTgtMy41OS04LTggczMuNTktOCw4LThzOCwzLjU5LDgsOFMxNi40MSwyMCwxMiwyMHoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-cut: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkuNjQgNy42NGMuMjMtLjUuMzYtMS4wNS4zNi0xLjY0IDAtMi4yMS0xLjc5LTQtNC00UzIgMy43OSAyIDZzMS43OSA0IDQgNGMuNTkgMCAxLjE0LS4xMyAxLjY0LS4zNkwxMCAxMmwtMi4zNiAyLjM2QzcuMTQgMTQuMTMgNi41OSAxNCA2IDE0Yy0yLjIxIDAtNCAxLjc5LTQgNHMxLjc5IDQgNCA0IDQtMS43OSA0LTRjMC0uNTktLjEzLTEuMTQtLjM2LTEuNjRMMTIgMTRsNyA3aDN2LTFMOS42NCA3LjY0ek02IDhjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTAgMTJjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTYtNy41Yy0uMjggMC0uNS0uMjItLjUtLjVzLjIyLS41LjUtLjUuNS4yMi41LjUtLjIyLjUtLjUuNXpNMTkgM2wtNiA2IDIgMiA3LTdWM3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-delete: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2cHgiIGhlaWdodD0iMTZweCI+CiAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIiAvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjI2MjYyIiBkPSJNNiAxOWMwIDEuMS45IDIgMiAyaDhjMS4xIDAgMi0uOSAyLTJWN0g2djEyek0xOSA0aC0zLjVsLTEtMWgtNWwtMSAxSDV2MmgxNFY0eiIgLz4KPC9zdmc+Cg==);
  --jp-icon-download: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDloLTRWM0g5djZINWw3IDcgNy03ek01IDE4djJoMTR2LTJINXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-duplicate: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGNsaXAtcnVsZT0iZXZlbm9kZCIgZD0iTTIuNzk5OTggMC44NzVIOC44OTU4MkM5LjIwMDYxIDAuODc1IDkuNDQ5OTggMS4xMzkxNCA5LjQ0OTk4IDEuNDYxOThDOS40NDk5OCAxLjc4NDgyIDkuMjAwNjEgMi4wNDg5NiA4Ljg5NTgyIDIuMDQ4OTZIMy4zNTQxNUMzLjA0OTM2IDIuMDQ4OTYgMi43OTk5OCAyLjMxMzEgMi43OTk5OCAyLjYzNTk0VjkuNjc5NjlDMi43OTk5OCAxMC4wMDI1IDIuNTUwNjEgMTAuMjY2NyAyLjI0NTgyIDEwLjI2NjdDMS45NDEwMyAxMC4yNjY3IDEuNjkxNjUgMTAuMDAyNSAxLjY5MTY1IDkuNjc5NjlWMi4wNDg5NkMxLjY5MTY1IDEuNDAzMjggMi4xOTA0IDAuODc1IDIuNzk5OTggMC44NzVaTTUuMzY2NjUgMTEuOVY0LjU1SDExLjA4MzNWMTEuOUg1LjM2NjY1Wk00LjE0MTY1IDQuMTQxNjdDNC4xNDE2NSAzLjY5MDYzIDQuNTA3MjggMy4zMjUgNC45NTgzMiAzLjMyNUgxMS40OTE3QzExLjk0MjcgMy4zMjUgMTIuMzA4MyAzLjY5MDYzIDEyLjMwODMgNC4xNDE2N1YxMi4zMDgzQzEyLjMwODMgMTIuNzU5NCAxMS45NDI3IDEzLjEyNSAxMS40OTE3IDEzLjEyNUg0Ljk1ODMyQzQuNTA3MjggMTMuMTI1IDQuMTQxNjUgMTIuNzU5NCA0LjE0MTY1IDEyLjMwODNWNC4xNDE2N1oiIGZpbGw9IiM2MTYxNjEiLz4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBkPSJNOS40MzU3NCA4LjI2NTA3SDguMzY0MzFWOS4zMzY1QzguMzY0MzEgOS40NTQzNSA4LjI2Nzg4IDkuNTUwNzggOC4xNTAwMiA5LjU1MDc4QzguMDMyMTcgOS41NTA3OCA3LjkzNTc0IDkuNDU0MzUgNy45MzU3NCA5LjMzNjVWOC4yNjUwN0g2Ljg2NDMxQzYuNzQ2NDUgOC4yNjUwNyA2LjY1MDAyIDguMTY4NjQgNi42NTAwMiA4LjA1MDc4QzYuNjUwMDIgNy45MzI5MiA2Ljc0NjQ1IDcuODM2NSA2Ljg2NDMxIDcuODM2NUg3LjkzNTc0VjYuNzY1MDdDNy45MzU3NCA2LjY0NzIxIDguMDMyMTcgNi41NTA3OCA4LjE1MDAyIDYuNTUwNzhDOC4yNjc4OCA2LjU1MDc4IDguMzY0MzEgNi42NDcyMSA4LjM2NDMxIDYuNzY1MDdWNy44MzY1SDkuNDM1NzRDOS41NTM2IDcuODM2NSA5LjY1MDAyIDcuOTMyOTIgOS42NTAwMiA4LjA1MDc4QzkuNjUwMDIgOC4xNjg2NCA5LjU1MzYgOC4yNjUwNyA5LjQzNTc0IDguMjY1MDdaIiBmaWxsPSIjNjE2MTYxIiBzdHJva2U9IiM2MTYxNjEiIHN0cm9rZS13aWR0aD0iMC41Ii8+Cjwvc3ZnPgo=);
  --jp-icon-edit: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMgMTcuMjVWMjFoMy43NUwxNy44MSA5Ljk0bC0zLjc1LTMuNzVMMyAxNy4yNXpNMjAuNzEgNy4wNGMuMzktLjM5LjM5LTEuMDIgMC0xLjQxbC0yLjM0LTIuMzRjLS4zOS0uMzktMS4wMi0uMzktMS40MSAwbC0xLjgzIDEuODMgMy43NSAzLjc1IDEuODMtMS44M3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-ellipses: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iNSIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxOSIgY3k9IjEyIiByPSIyIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-error: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj48Y2lyY2xlIGN4PSIxMiIgY3k9IjE5IiByPSIyIi8+PHBhdGggZD0iTTEwIDNoNHYxMmgtNHoiLz48L2c+CjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0wIDBoMjR2MjRIMHoiLz4KPC9zdmc+Cg==);
  --jp-icon-expand-all: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTggMmMxIDAgMTEgMCAxMiAwczIgMSAyIDJjMCAxIDAgMTEgMCAxMnMwIDItMiAyQzIwIDE0IDIwIDQgMjAgNFMxMCA0IDYgNGMwLTIgMS0yIDItMnoiIC8+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTE4IDhjMC0xLTEtMi0yLTJTNSA2IDQgNnMtMiAxLTIgMmMwIDEgMCAxMSAwIDEyczEgMiAyIDJjMSAwIDExIDAgMTIgMHMyLTEgMi0yYzAtMSAwLTExIDAtMTJ6bS0yIDB2MTJINFY4eiIgLz4KICAgICAgICA8cGF0aCBkPSJNMTEgMTBIOXYzSDZ2MmgzdjNoMnYtM2gzdi0yaC0zeiIgLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-extension: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwLjUgMTFIMTlWN2MwLTEuMS0uOS0yLTItMmgtNFYzLjVDMTMgMi4xMiAxMS44OCAxIDEwLjUgMVM4IDIuMTIgOCAzLjVWNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAydjMuOEgzLjVjMS40OSAwIDIuNyAxLjIxIDIuNyAyLjdzLTEuMjEgMi43LTIuNyAyLjdIMlYyMGMwIDEuMS45IDIgMiAyaDMuOHYtMS41YzAtMS40OSAxLjIxLTIuNyAyLjctMi43IDEuNDkgMCAyLjcgMS4yMSAyLjcgMi43VjIySDE3YzEuMSAwIDItLjkgMi0ydi00aDEuNWMxLjM4IDAgMi41LTEuMTIgMi41LTIuNVMyMS44OCAxMSAyMC41IDExeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-fast-forward: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTQgMThsOC41LTZMNCA2djEyem05LTEydjEybDguNS02TDEzIDZ6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-file-upload: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkgMTZoNnYtNmg0bC03LTctNyA3aDR6bS00IDJoMTR2Mkg1eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-file: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuMyA4LjJsLTUuNS01LjVjLS4zLS4zLS43LS41LTEuMi0uNUgzLjljLS44LjEtMS42LjktMS42IDEuOHYxNC4xYzAgLjkuNyAxLjYgMS42IDEuNmgxNC4yYy45IDAgMS42LS43IDEuNi0xLjZWOS40Yy4xLS41LS4xLS45LS40LTEuMnptLTUuOC0zLjNsMy40IDMuNmgtMy40VjQuOXptMy45IDEyLjdINC43Yy0uMSAwLS4yIDAtLjItLjJWNC43YzAtLjIuMS0uMy4yLS4zaDcuMnY0LjRzMCAuOC4zIDEuMWMuMy4zIDEuMS4zIDEuMS4zaDQuM3Y3LjJzLS4xLjItLjIuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-filter-dot: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTE0LDEyVjE5Ljg4QzE0LjA0LDIwLjE4IDEzLjk0LDIwLjUgMTMuNzEsMjAuNzFDMTMuMzIsMjEuMSAxMi42OSwyMS4xIDEyLjMsMjAuNzFMMTAuMjksMTguN0MxMC4wNiwxOC40NyA5Ljk2LDE4LjE2IDEwLDE3Ljg3VjEySDkuOTdMNC4yMSw0LjYyQzMuODcsNC4xOSAzLjk1LDMuNTYgNC4zOCwzLjIyQzQuNTcsMy4wOCA0Ljc4LDMgNSwzVjNIMTlWM0MxOS4yMiwzIDE5LjQzLDMuMDggMTkuNjIsMy4yMkMyMC4wNSwzLjU2IDIwLjEzLDQuMTkgMTkuNzksNC42MkwxNC4wMywxMkgxNFoiIC8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWRvdCIgZmlsbD0iI0ZGRiI+CiAgICA8Y2lyY2xlIGN4PSIxOCIgY3k9IjE3IiByPSIzIj48L2NpcmNsZT4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-filter-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEwIDE4aDR2LTJoLTR2MnpNMyA2djJoMThWNkgzem0zIDdoMTJ2LTJINnYyeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-filter: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTE0LDEyVjE5Ljg4QzE0LjA0LDIwLjE4IDEzLjk0LDIwLjUgMTMuNzEsMjAuNzFDMTMuMzIsMjEuMSAxMi42OSwyMS4xIDEyLjMsMjAuNzFMMTAuMjksMTguN0MxMC4wNiwxOC40NyA5Ljk2LDE4LjE2IDEwLDE3Ljg3VjEySDkuOTdMNC4yMSw0LjYyQzMuODcsNC4xOSAzLjk1LDMuNTYgNC4zOCwzLjIyQzQuNTcsMy4wOCA0Ljc4LDMgNSwzVjNIMTlWM0MxOS4yMiwzIDE5LjQzLDMuMDggMTkuNjIsMy4yMkMyMC4wNSwzLjU2IDIwLjEzLDQuMTkgMTkuNzksNC42MkwxNC4wMywxMkgxNFoiIC8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-folder-favorite: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjRweCIgdmlld0JveD0iMCAwIDI0IDI0IiB3aWR0aD0iMjRweCIgZmlsbD0iIzAwMDAwMCI+CiAgPHBhdGggZD0iTTAgMGgyNHYyNEgwVjB6IiBmaWxsPSJub25lIi8+PHBhdGggY2xhc3M9ImpwLWljb24zIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxNjE2MSIgZD0iTTIwIDZoLThsLTItMkg0Yy0xLjEgMC0yIC45LTIgMnYxMmMwIDEuMS45IDIgMiAyaDE2YzEuMSAwIDItLjkgMi0yVjhjMC0xLjEtLjktMi0yLTJ6bS0yLjA2IDExTDE1IDE1LjI4IDEyLjA2IDE3bC43OC0zLjMzLTIuNTktMi4yNCAzLjQxLS4yOUwxNSA4bDEuMzQgMy4xNCAzLjQxLjI5LTIuNTkgMi4yNC43OCAzLjMzeiIvPgo8L3N2Zz4K);
  --jp-icon-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY4YzAtMS4xLS45LTItMi0yaC04bC0yLTJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-home: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjRweCIgdmlld0JveD0iMCAwIDI0IDI0IiB3aWR0aD0iMjRweCIgZmlsbD0iIzAwMDAwMCI+CiAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPjxwYXRoIGNsYXNzPSJqcC1pY29uMyBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xMCAyMHYtNmg0djZoNXYtOGgzTDEyIDMgMiAxMmgzdjh6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-html5: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMDAiIGQ9Ik0xMDguNCAwaDIzdjIyLjhoMjEuMlYwaDIzdjY5aC0yM1Y0NmgtMjF2MjNoLTIzLjJNMjA2IDIzaC0yMC4zVjBoNjMuN3YyM0gyMjl2NDZoLTIzbTUzLjUtNjloMjQuMWwxNC44IDI0LjNMMzEzLjIgMGgyNC4xdjY5aC0yM1YzNC44bC0xNi4xIDI0LjgtMTYuMS0yNC44VjY5aC0yMi42bTg5LjItNjloMjN2NDYuMmgzMi42VjY5aC01NS42Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI2U0NGQyNiIgZD0iTTEwNy42IDQ3MWwtMzMtMzcwLjRoMzYyLjhsLTMzIDM3MC4yTDI1NS43IDUxMiIvPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNmMTY1MjkiIGQ9Ik0yNTYgNDgwLjVWMTMxaDE0OC4zTDM3NiA0NDciLz4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNlYmViZWIiIGQ9Ik0xNDIgMTc2LjNoMTE0djQ1LjRoLTY0LjJsNC4yIDQ2LjVoNjB2NDUuM0gxNTQuNG0yIDIyLjhIMjAybDMuMiAzNi4zIDUwLjggMTMuNnY0Ny40bC05My4yLTI2Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIiBmaWxsPSIjZmZmIiBkPSJNMzY5LjYgMTc2LjNIMjU1Ljh2NDUuNGgxMDkuNm0tNC4xIDQ2LjVIMjU1Ljh2NDUuNGg1NmwtNS4zIDU5LTUwLjcgMTMuNnY0Ny4ybDkzLTI1LjgiLz4KPC9zdmc+Cg==);
  --jp-icon-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1icmFuZDQganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNGRkYiIGQ9Ik0yLjIgMi4yaDE3LjV2MTcuNUgyLjJ6Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzNGNTFCNSIgZD0iTTIuMiAyLjJ2MTcuNWgxNy41bC4xLTE3LjVIMi4yem0xMi4xIDIuMmMxLjIgMCAyLjIgMSAyLjIgMi4ycy0xIDIuMi0yLjIgMi4yLTIuMi0xLTIuMi0yLjIgMS0yLjIgMi4yLTIuMnpNNC40IDE3LjZsMy4zLTguOCAzLjMgNi42IDIuMi0zLjIgNC40IDUuNEg0LjR6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-info: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUwLjk3OCA1MC45NzgiPgoJPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KCQk8cGF0aCBkPSJNNDMuNTIsNy40NThDMzguNzExLDIuNjQ4LDMyLjMwNywwLDI1LjQ4OSwwQzE4LjY3LDAsMTIuMjY2LDIuNjQ4LDcuNDU4LDcuNDU4CgkJCWMtOS45NDMsOS45NDEtOS45NDMsMjYuMTE5LDAsMzYuMDYyYzQuODA5LDQuODA5LDExLjIxMiw3LjQ1NiwxOC4wMzEsNy40NThjMCwwLDAuMDAxLDAsMC4wMDIsMAoJCQljNi44MTYsMCwxMy4yMjEtMi42NDgsMTguMDI5LTcuNDU4YzQuODA5LTQuODA5LDcuNDU3LTExLjIxMiw3LjQ1Ny0xOC4wM0M1MC45NzcsMTguNjcsNDguMzI4LDEyLjI2Niw0My41Miw3LjQ1OHoKCQkJIE00Mi4xMDYsNDIuMTA1Yy00LjQzMiw0LjQzMS0xMC4zMzIsNi44NzItMTYuNjE1LDYuODcyaC0wLjAwMmMtNi4yODUtMC4wMDEtMTIuMTg3LTIuNDQxLTE2LjYxNy02Ljg3MgoJCQljLTkuMTYyLTkuMTYzLTkuMTYyLTI0LjA3MSwwLTMzLjIzM0MxMy4zMDMsNC40NCwxOS4yMDQsMiwyNS40ODksMmM2LjI4NCwwLDEyLjE4NiwyLjQ0LDE2LjYxNyw2Ljg3MgoJCQljNC40MzEsNC40MzEsNi44NzEsMTAuMzMyLDYuODcxLDE2LjYxN0M0OC45NzcsMzEuNzcyLDQ2LjUzNiwzNy42NzUsNDIuMTA2LDQyLjEwNXoiLz4KCQk8cGF0aCBkPSJNMjMuNTc4LDMyLjIxOGMtMC4wMjMtMS43MzQsMC4xNDMtMy4wNTksMC40OTYtMy45NzJjMC4zNTMtMC45MTMsMS4xMS0xLjk5NywyLjI3Mi0zLjI1MwoJCQljMC40NjgtMC41MzYsMC45MjMtMS4wNjIsMS4zNjctMS41NzVjMC42MjYtMC43NTMsMS4xMDQtMS40NzgsMS40MzYtMi4xNzVjMC4zMzEtMC43MDcsMC40OTUtMS41NDEsMC40OTUtMi41CgkJCWMwLTEuMDk2LTAuMjYtMi4wODgtMC43NzktMi45NzljLTAuNTY1LTAuODc5LTEuNTAxLTEuMzM2LTIuODA2LTEuMzY5Yy0xLjgwMiwwLjA1Ny0yLjk4NSwwLjY2Ny0zLjU1LDEuODMyCgkJCWMtMC4zMDEsMC41MzUtMC41MDMsMS4xNDEtMC42MDcsMS44MTRjLTAuMTM5LDAuNzA3LTAuMjA3LDEuNDMyLTAuMjA3LDIuMTc0aC0yLjkzN2MtMC4wOTEtMi4yMDgsMC40MDctNC4xMTQsMS40OTMtNS43MTkKCQkJYzEuMDYyLTEuNjQsMi44NTUtMi40ODEsNS4zNzgtMi41MjdjMi4xNiwwLjAyMywzLjg3NCwwLjYwOCw1LjE0MSwxLjc1OGMxLjI3OCwxLjE2LDEuOTI5LDIuNzY0LDEuOTUsNC44MTEKCQkJYzAsMS4xNDItMC4xMzcsMi4xMTEtMC40MSwyLjkxMWMtMC4zMDksMC44NDUtMC43MzEsMS41OTMtMS4yNjgsMi4yNDNjLTAuNDkyLDAuNjUtMS4wNjgsMS4zMTgtMS43MywyLjAwMgoJCQljLTAuNjUsMC42OTctMS4zMTMsMS40NzktMS45ODcsMi4zNDZjLTAuMjM5LDAuMzc3LTAuNDI5LDAuNzc3LTAuNTY1LDEuMTk5Yy0wLjE2LDAuOTU5LTAuMjE3LDEuOTUxLTAuMTcxLDIuOTc5CgkJCUMyNi41ODksMzIuMjE4LDIzLjU3OCwzMi4yMTgsMjMuNTc4LDMyLjIxOHogTTIzLjU3OCwzOC4yMnYtMy40ODRoMy4wNzZ2My40ODRIMjMuNTc4eiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-inspector: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaW5zcGVjdG9yLWljb24tY29sb3IganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY2YzAtMS4xLS45LTItMi0yem0tNSAxNEg0di00aDExdjR6bTAtNUg0VjloMTF2NHptNSA1aC00VjloNHY5eiIvPgo8L3N2Zz4K);
  --jp-icon-json: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtanNvbi1pY29uLWNvbG9yIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI0Y5QTgyNSI+CiAgICA8cGF0aCBkPSJNMjAuMiAxMS44Yy0xLjYgMC0xLjcuNS0xLjcgMSAwIC40LjEuOS4xIDEuMy4xLjUuMS45LjEgMS4zIDAgMS43LTEuNCAyLjMtMy41IDIuM2gtLjl2LTEuOWguNWMxLjEgMCAxLjQgMCAxLjQtLjggMC0uMyAwLS42LS4xLTEgMC0uNC0uMS0uOC0uMS0xLjIgMC0xLjMgMC0xLjggMS4zLTItMS4zLS4yLTEuMy0uNy0xLjMtMiAwLS40LjEtLjguMS0xLjIuMS0uNC4xLS43LjEtMSAwLS44LS40LS43LTEuNC0uOGgtLjVWNC4xaC45YzIuMiAwIDMuNS43IDMuNSAyLjMgMCAuNC0uMS45LS4xIDEuMy0uMS41LS4xLjktLjEgMS4zIDAgLjUuMiAxIDEuNyAxdjEuOHpNMS44IDEwLjFjMS42IDAgMS43LS41IDEuNy0xIDAtLjQtLjEtLjktLjEtMS4zLS4xLS41LS4xLS45LS4xLTEuMyAwLTEuNiAxLjQtMi4zIDMuNS0yLjNoLjl2MS45aC0uNWMtMSAwLTEuNCAwLTEuNC44IDAgLjMgMCAuNi4xIDEgMCAuMi4xLjYuMSAxIDAgMS4zIDAgMS44LTEuMyAyQzYgMTEuMiA2IDExLjcgNiAxM2MwIC40LS4xLjgtLjEgMS4yLS4xLjMtLjEuNy0uMSAxIDAgLjguMy44IDEuNC44aC41djEuOWgtLjljLTIuMSAwLTMuNS0uNi0zLjUtMi4zIDAtLjQuMS0uOS4xLTEuMy4xLS41LjEtLjkuMS0xLjMgMC0uNS0uMi0xLTEuNy0xdi0xLjl6Ii8+CiAgICA8Y2lyY2xlIGN4PSIxMSIgY3k9IjEzLjgiIHI9IjIuMSIvPgogICAgPGNpcmNsZSBjeD0iMTEiIGN5PSI4LjIiIHI9IjIuMSIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-julia: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDMyNSAzMDAiPgogIDxnIGNsYXNzPSJqcC1icmFuZDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjY2IzYzMzIj4KICAgIDxwYXRoIGQ9Ik0gMTUwLjg5ODQzOCAyMjUgQyAxNTAuODk4NDM4IDI2Ni40MjE4NzUgMTE3LjMyMDMxMiAzMDAgNzUuODk4NDM4IDMwMCBDIDM0LjQ3NjU2MiAzMDAgMC44OTg0MzggMjY2LjQyMTg3NSAwLjg5ODQzOCAyMjUgQyAwLjg5ODQzOCAxODMuNTc4MTI1IDM0LjQ3NjU2MiAxNTAgNzUuODk4NDM4IDE1MCBDIDExNy4zMjAzMTIgMTUwIDE1MC44OTg0MzggMTgzLjU3ODEyNSAxNTAuODk4NDM4IDIyNSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzM4OTgyNiI+CiAgICA8cGF0aCBkPSJNIDIzNy41IDc1IEMgMjM3LjUgMTE2LjQyMTg3NSAyMDMuOTIxODc1IDE1MCAxNjIuNSAxNTAgQyAxMjEuMDc4MTI1IDE1MCA4Ny41IDExNi40MjE4NzUgODcuNSA3NSBDIDg3LjUgMzMuNTc4MTI1IDEyMS4wNzgxMjUgMCAxNjIuNSAwIEMgMjAzLjkyMTg3NSAwIDIzNy41IDMzLjU3ODEyNSAyMzcuNSA3NSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzk1NThiMiI+CiAgICA8cGF0aCBkPSJNIDMyNC4xMDE1NjIgMjI1IEMgMzI0LjEwMTU2MiAyNjYuNDIxODc1IDI5MC41MjM0MzggMzAwIDI0OS4xMDE1NjIgMzAwIEMgMjA3LjY3OTY4OCAzMDAgMTc0LjEwMTU2MiAyNjYuNDIxODc1IDE3NC4xMDE1NjIgMjI1IEMgMTc0LjEwMTU2MiAxODMuNTc4MTI1IDIwNy42Nzk2ODggMTUwIDI0OS4xMDE1NjIgMTUwIEMgMjkwLjUyMzQzOCAxNTAgMzI0LjEwMTU2MiAxODMuNTc4MTI1IDMyNC4xMDE1NjIgMjI1Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-jupyter-favicon: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTUyIiBoZWlnaHQ9IjE2NSIgdmlld0JveD0iMCAwIDE1MiAxNjUiIHZlcnNpb249IjEuMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgPGcgY2xhc3M9ImpwLWp1cHl0ZXItaWNvbi1jb2xvciIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA3ODk0NywgMTEwLjU4MjkyNykiIGQ9Ik03NS45NDIyODQyLDI5LjU4MDQ1NjEgQzQzLjMwMjM5NDcsMjkuNTgwNDU2MSAxNC43OTY3ODMyLDE3LjY1MzQ2MzQgMCwwIEM1LjUxMDgzMjExLDE1Ljg0MDY4MjkgMTUuNzgxNTM4OSwyOS41NjY3NzMyIDI5LjM5MDQ5NDcsMzkuMjc4NDE3MSBDNDIuOTk5Nyw0OC45ODk4NTM3IDU5LjI3MzcsNTQuMjA2NzgwNSA3NS45NjA1Nzg5LDU0LjIwNjc4MDUgQzkyLjY0NzQ1NzksNTQuMjA2NzgwNSAxMDguOTIxNDU4LDQ4Ljk4OTg1MzcgMTIyLjUzMDY2MywzOS4yNzg0MTcxIEMxMzYuMTM5NDUzLDI5LjU2Njc3MzIgMTQ2LjQxMDI4NCwxNS44NDA2ODI5IDE1MS45MjExNTgsMCBDMTM3LjA4Nzg2OCwxNy42NTM0NjM0IDEwOC41ODI1ODksMjkuNTgwNDU2MSA3NS45NDIyODQyLDI5LjU4MDQ1NjEgTDc1Ljk0MjI4NDIsMjkuNTgwNDU2MSBaIiAvPgogICAgPHBhdGggdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMzczNjgsIDAuNzA0ODc4KSIgZD0iTTc1Ljk3ODQ1NzksMjQuNjI2NDA3MyBDMTA4LjYxODc2MywyNC42MjY0MDczIDEzNy4xMjQ0NTgsMzYuNTUzNDQxNSAxNTEuOTIxMTU4LDU0LjIwNjc4MDUgQzE0Ni40MTAyODQsMzguMzY2MjIyIDEzNi4xMzk0NTMsMjQuNjQwMTMxNyAxMjIuNTMwNjYzLDE0LjkyODQ4NzggQzEwOC45MjE0NTgsNS4yMTY4NDM5IDkyLjY0NzQ1NzksMCA3NS45NjA1Nzg5LDAgQzU5LjI3MzcsMCA0Mi45OTk3LDUuMjE2ODQzOSAyOS4zOTA0OTQ3LDE0LjkyODQ4NzggQzE1Ljc4MTUzODksMjQuNjQwMTMxNyA1LjUxMDgzMjExLDM4LjM2NjIyMiAwLDU0LjIwNjc4MDUgQzE0LjgzMzA4MTYsMzYuNTg5OTI5MyA0My4zMzg1Njg0LDI0LjYyNjQwNzMgNzUuOTc4NDU3OSwyNC42MjY0MDczIEw3NS45Nzg0NTc5LDI0LjYyNjQwNzMgWiIgLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-jupyter: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzkiIGhlaWdodD0iNTEiIHZpZXdCb3g9IjAgMCAzOSA1MSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMTYzOCAtMjI4MSkiPgogICAgIDxnIGNsYXNzPSJqcC1qdXB5dGVyLWljb24tY29sb3IiIGZpbGw9IiNGMzc3MjYiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5Ljc0IDIzMTEuOTgpIiBkPSJNIDE4LjI2NDYgNy4xMzQxMUMgMTAuNDE0NSA3LjEzNDExIDMuNTU4NzIgNC4yNTc2IDAgMEMgMS4zMjUzOSAzLjgyMDQgMy43OTU1NiA3LjEzMDgxIDcuMDY4NiA5LjQ3MzAzQyAxMC4zNDE3IDExLjgxNTIgMTQuMjU1NyAxMy4wNzM0IDE4LjI2OSAxMy4wNzM0QyAyMi4yODIzIDEzLjA3MzQgMjYuMTk2MyAxMS44MTUyIDI5LjQ2OTQgOS40NzMwM0MgMzIuNzQyNCA3LjEzMDgxIDM1LjIxMjYgMy44MjA0IDM2LjUzOCAwQyAzMi45NzA1IDQuMjU3NiAyNi4xMTQ4IDcuMTM0MTEgMTguMjY0NiA3LjEzNDExWiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5LjczIDIyODUuNDgpIiBkPSJNIDE4LjI3MzMgNS45MzkzMUMgMjYuMTIzNSA1LjkzOTMxIDMyLjk3OTMgOC44MTU4MyAzNi41MzggMTMuMDczNEMgMzUuMjEyNiA5LjI1MzAzIDMyLjc0MjQgNS45NDI2MiAyOS40Njk0IDMuNjAwNEMgMjYuMTk2MyAxLjI1ODE4IDIyLjI4MjMgMCAxOC4yNjkgMEMgMTQuMjU1NyAwIDEwLjM0MTcgMS4yNTgxOCA3LjA2ODYgMy42MDA0QyAzLjc5NTU2IDUuOTQyNjIgMS4zMjUzOSA5LjI1MzAzIDAgMTMuMDczNEMgMy41Njc0NSA4LjgyNDYzIDEwLjQyMzIgNS45MzkzMSAxOC4yNzMzIDUuOTM5MzFaIi8+CiAgICA8L2c+CiAgICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjY5LjMgMjI4MS4zMSkiIGQ9Ik0gNS44OTM1MyAyLjg0NEMgNS45MTg4OSAzLjQzMTY1IDUuNzcwODUgNC4wMTM2NyA1LjQ2ODE1IDQuNTE2NDVDIDUuMTY1NDUgNS4wMTkyMiA0LjcyMTY4IDUuNDIwMTUgNC4xOTI5OSA1LjY2ODUxQyAzLjY2NDMgNS45MTY4OCAzLjA3NDQ0IDYuMDAxNTEgMi40OTgwNSA1LjkxMTcxQyAxLjkyMTY2IDUuODIxOSAxLjM4NDYzIDUuNTYxNyAwLjk1NDg5OCA1LjE2NDAxQyAwLjUyNTE3IDQuNzY2MzMgMC4yMjIwNTYgNC4yNDkwMyAwLjA4MzkwMzcgMy42Nzc1N0MgLTAuMDU0MjQ4MyAzLjEwNjExIC0wLjAyMTIzIDIuNTA2MTcgMC4xNzg3ODEgMS45NTM2NEMgMC4zNzg3OTMgMS40MDExIDAuNzM2ODA5IDAuOTIwODE3IDEuMjA3NTQgMC41NzM1MzhDIDEuNjc4MjYgMC4yMjYyNTkgMi4yNDA1NSAwLjAyNzU5MTkgMi44MjMyNiAwLjAwMjY3MjI5QyAzLjYwMzg5IC0wLjAzMDcxMTUgNC4zNjU3MyAwLjI0OTc4OSA0Ljk0MTQyIDAuNzgyNTUxQyA1LjUxNzExIDEuMzE1MzEgNS44NTk1NiAyLjA1Njc2IDUuODkzNTMgMi44NDRaIi8+CiAgICAgIDxwYXRoIHRyYW5zZm9ybT0idHJhbnNsYXRlKDE2MzkuOCAyMzIzLjgxKSIgZD0iTSA3LjQyNzg5IDMuNTgzMzhDIDcuNDYwMDggNC4zMjQzIDcuMjczNTUgNS4wNTgxOSA2Ljg5MTkzIDUuNjkyMTNDIDYuNTEwMzEgNi4zMjYwNyA1Ljk1MDc1IDYuODMxNTYgNS4yODQxMSA3LjE0NDZDIDQuNjE3NDcgNy40NTc2MyAzLjg3MzcxIDcuNTY0MTQgMy4xNDcwMiA3LjQ1MDYzQyAyLjQyMDMyIDcuMzM3MTIgMS43NDMzNiA3LjAwODcgMS4yMDE4NCA2LjUwNjk1QyAwLjY2MDMyOCA2LjAwNTIgMC4yNzg2MSA1LjM1MjY4IDAuMTA1MDE3IDQuNjMyMDJDIC0wLjA2ODU3NTcgMy45MTEzNSAtMC4wMjYyMzYxIDMuMTU0OTQgMC4yMjY2NzUgMi40NTg1NkMgMC40Nzk1ODcgMS43NjIxNyAwLjkzMTY5NyAxLjE1NzEzIDEuNTI1NzYgMC43MjAwMzNDIDIuMTE5ODMgMC4yODI5MzUgMi44MjkxNCAwLjAzMzQzOTUgMy41NjM4OSAwLjAwMzEzMzQ0QyA0LjU0NjY3IC0wLjAzNzQwMzMgNS41MDUyOSAwLjMxNjcwNiA2LjIyOTYxIDAuOTg3ODM1QyA2Ljk1MzkzIDEuNjU4OTYgNy4zODQ4NCAyLjU5MjM1IDcuNDI3ODkgMy41ODMzOEwgNy40Mjc4OSAzLjU4MzM4WiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM4LjM2IDIyODYuMDYpIiBkPSJNIDIuMjc0NzEgNC4zOTYyOUMgMS44NDM2MyA0LjQxNTA4IDEuNDE2NzEgNC4zMDQ0NSAxLjA0Nzk5IDQuMDc4NDNDIDAuNjc5MjY4IDMuODUyNCAwLjM4NTMyOCAzLjUyMTE0IDAuMjAzMzcxIDMuMTI2NTZDIDAuMDIxNDEzNiAyLjczMTk4IC0wLjA0MDM3OTggMi4yOTE4MyAwLjAyNTgxMTYgMS44NjE4MUMgMC4wOTIwMDMxIDEuNDMxOCAwLjI4MzIwNCAxLjAzMTI2IDAuNTc1MjEzIDAuNzEwODgzQyAwLjg2NzIyMiAwLjM5MDUxIDEuMjQ2OTEgMC4xNjQ3MDggMS42NjYyMiAwLjA2MjA1OTJDIDIuMDg1NTMgLTAuMDQwNTg5NyAyLjUyNTYxIC0wLjAxNTQ3MTQgMi45MzA3NiAwLjEzNDIzNUMgMy4zMzU5MSAwLjI4Mzk0MSAzLjY4NzkyIDAuNTUxNTA1IDMuOTQyMjIgMC45MDMwNkMgNC4xOTY1MiAxLjI1NDYyIDQuMzQxNjkgMS42NzQzNiA0LjM1OTM1IDIuMTA5MTZDIDQuMzgyOTkgMi42OTEwNyA0LjE3Njc4IDMuMjU4NjkgMy43ODU5NyAzLjY4NzQ2QyAzLjM5NTE2IDQuMTE2MjQgMi44NTE2NiA0LjM3MTE2IDIuMjc0NzEgNC4zOTYyOUwgMi4yNzQ3MSA0LjM5NjI5WiIvPgogICAgPC9nPgogIDwvZz4+Cjwvc3ZnPgo=);
  --jp-icon-jupyterlab-wordmark: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMDAiIHZpZXdCb3g9IjAgMCAxODYwLjggNDc1Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0RTRFNEUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDQ4MC4xMzY0MDEsIDY0LjI3MTQ5MykiPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMDAwMDAsIDU4Ljg3NTU2NikiPgogICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA4NzYwMywgMC4xNDAyOTQpIj4KICAgICAgICA8cGF0aCBkPSJNLTQyNi45LDE2OS44YzAsNDguNy0zLjcsNjQuNy0xMy42LDc2LjRjLTEwLjgsMTAtMjUsMTUuNS0zOS43LDE1LjVsMy43LDI5IGMyMi44LDAuMyw0NC44LTcuOSw2MS45LTIzLjFjMTcuOC0xOC41LDI0LTQ0LjEsMjQtODMuM1YwSC00Mjd2MTcwLjFMLTQyNi45LDE2OS44TC00MjYuOSwxNjkuOHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTU1LjA0NTI5NiwgNTYuODM3MTA0KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuNTYyNDUzLCAxLjc5OTg0MikiPgogICAgICAgIDxwYXRoIGQ9Ik0tMzEyLDE0OGMwLDIxLDAsMzkuNSwxLjcsNTUuNGgtMzEuOGwtMi4xLTMzLjNoLTAuOGMtNi43LDExLjYtMTYuNCwyMS4zLTI4LDI3LjkgYy0xMS42LDYuNi0yNC44LDEwLTM4LjIsOS44Yy0zMS40LDAtNjktMTcuNy02OS04OVYwaDM2LjR2MTEyLjdjMCwzOC43LDExLjYsNjQuNyw0NC42LDY0LjdjMTAuMy0wLjIsMjAuNC0zLjUsMjguOS05LjQgYzguNS01LjksMTUuMS0xNC4zLDE4LjktMjMuOWMyLjItNi4xLDMuMy0xMi41LDMuMy0xOC45VjAuMmgzNi40VjE0OEgtMzEyTC0zMTIsMTQ4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzOTAuMDEzMzIyLCA1My40Nzk2MzgpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS43MDY0NTgsIDAuMjMxNDI1KSI+CiAgICAgICAgPHBhdGggZD0iTS00NzguNiw3MS40YzAtMjYtMC44LTQ3LTEuNy02Ni43aDMyLjdsMS43LDM0LjhoMC44YzcuMS0xMi41LDE3LjUtMjIuOCwzMC4xLTI5LjcgYzEyLjUtNywyNi43LTEwLjMsNDEtOS44YzQ4LjMsMCw4NC43LDQxLjcsODQuNywxMDMuM2MwLDczLjEtNDMuNywxMDkuMi05MSwxMDkuMmMtMTIuMSwwLjUtMjQuMi0yLjItMzUtNy44IGMtMTAuOC01LjYtMTkuOS0xMy45LTI2LjYtMjQuMmgtMC44VjI5MWgtMzZ2LTIyMEwtNDc4LjYsNzEuNEwtNDc4LjYsNzEuNHogTS00NDIuNiwxMjUuNmMwLjEsNS4xLDAuNiwxMC4xLDEuNywxNS4xIGMzLDEyLjMsOS45LDIzLjMsMTkuOCwzMS4xYzkuOSw3LjgsMjIuMSwxMi4xLDM0LjcsMTIuMWMzOC41LDAsNjAuNy0zMS45LDYwLjctNzguNWMwLTQwLjctMjEuMS03NS42LTU5LjUtNzUuNiBjLTEyLjksMC40LTI1LjMsNS4xLTM1LjMsMTMuNGMtOS45LDguMy0xNi45LDE5LjctMTkuNiwzMi40Yy0xLjUsNC45LTIuMywxMC0yLjUsMTUuMVYxMjUuNkwtNDQyLjYsMTI1LjZMLTQ0Mi42LDEyNS42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg2MDYuNzQwNzI2LCA1Ni44MzcxMDQpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC43NTEyMjYsIDEuOTg5Mjk5KSI+CiAgICAgICAgPHBhdGggZD0iTS00NDAuOCwwbDQzLjcsMTIwLjFjNC41LDEzLjQsOS41LDI5LjQsMTIuOCw0MS43aDAuOGMzLjctMTIuMiw3LjktMjcuNywxMi44LTQyLjQgbDM5LjctMTE5LjJoMzguNUwtMzQ2LjksMTQ1Yy0yNiw2OS43LTQzLjcsMTA1LjQtNjguNiwxMjcuMmMtMTIuNSwxMS43LTI3LjksMjAtNDQuNiwyMy45bC05LjEtMzEuMSBjMTEuNy0zLjksMjIuNS0xMC4xLDMxLjgtMTguMWMxMy4yLTExLjEsMjMuNy0yNS4yLDMwLjYtNDEuMmMxLjUtMi44LDIuNS01LjcsMi45LTguOGMtMC4zLTMuMy0xLjItNi42LTIuNS05LjdMLTQ4MC4yLDAuMSBoMzkuN0wtNDQwLjgsMEwtNDQwLjgsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoODIyLjc0ODEwNCwgMC4wMDAwMDApIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS40NjQwNTAsIDAuMzc4OTE0KSI+CiAgICAgICAgPHBhdGggZD0iTS00MTMuNywwdjU4LjNoNTJ2MjguMmgtNTJWMTk2YzAsMjUsNywzOS41LDI3LjMsMzkuNWM3LjEsMC4xLDE0LjItMC43LDIxLjEtMi41IGwxLjcsMjcuN2MtMTAuMywzLjctMjEuMyw1LjQtMzIuMiw1Yy03LjMsMC40LTE0LjYtMC43LTIxLjMtMy40Yy02LjgtMi43LTEyLjktNi44LTE3LjktMTIuMWMtMTAuMy0xMC45LTE0LjEtMjktMTQuMS01Mi45IFY4Ni41aC0zMVY1OC4zaDMxVjkuNkwtNDEzLjcsMEwtNDEzLjcsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOTc0LjQzMzI4NiwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAuOTkwMDM0LCAwLjYxMDMzOSkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDQ1LjgsMTEzYzAuOCw1MCwzMi4yLDcwLjYsNjguNiw3MC42YzE5LDAuNiwzNy45LTMsNTUuMy0xMC41bDYuMiwyNi40IGMtMjAuOSw4LjktNDMuNSwxMy4xLTY2LjIsMTIuNmMtNjEuNSwwLTk4LjMtNDEuMi05OC4zLTEwMi41Qy00ODAuMiw0OC4yLTQ0NC43LDAtMzg2LjUsMGM2NS4yLDAsODIuNyw1OC4zLDgyLjcsOTUuNyBjLTAuMSw1LjgtMC41LDExLjUtMS4yLDE3LjJoLTE0MC42SC00NDUuOEwtNDQ1LjgsMTEzeiBNLTMzOS4yLDg2LjZjMC40LTIzLjUtOS41LTYwLjEtNTAuNC02MC4xIGMtMzYuOCwwLTUyLjgsMzQuNC01NS43LDYwLjFILTMzOS4yTC0zMzkuMiw4Ni42TC0zMzkuMiw4Ni42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMjAxLjk2MTA1OCwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuMTc5NjQwLCAwLjcwNTA2OCkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDc4LjYsNjhjMC0yMy45LTAuNC00NC41LTEuNy02My40aDMxLjhsMS4yLDM5LjloMS43YzkuMS0yNy4zLDMxLTQ0LjUsNTUuMy00NC41IGMzLjUtMC4xLDcsMC40LDEwLjMsMS4ydjM0LjhjLTQuMS0wLjktOC4yLTEuMy0xMi40LTEuMmMtMjUuNiwwLTQzLjcsMTkuNy00OC43LDQ3LjRjLTEsNS43LTEuNiwxMS41LTEuNywxNy4ydjEwOC4zaC0zNlY2OCBMLTQ3OC42LDY4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCBkPSJNMTM1Mi4zLDMyNi4yaDM3VjI4aC0zN1YzMjYuMnogTTE2MDQuOCwzMjYuMmMtMi41LTEzLjktMy40LTMxLjEtMy40LTQ4Ljd2LTc2IGMwLTQwLjctMTUuMS04My4xLTc3LjMtODMuMWMtMjUuNiwwLTUwLDcuMS02Ni44LDE4LjFsOC40LDI0LjRjMTQuMy05LjIsMzQtMTUuMSw1My0xNS4xYzQxLjYsMCw0Ni4yLDMwLjIsNDYuMiw0N3Y0LjIgYy03OC42LTAuNC0xMjIuMywyNi41LTEyMi4zLDc1LjZjMCwyOS40LDIxLDU4LjQsNjIuMiw1OC40YzI5LDAsNTAuOS0xNC4zLDYyLjItMzAuMmgxLjNsMi45LDI1LjZIMTYwNC44eiBNMTU2NS43LDI1Ny43IGMwLDMuOC0wLjgsOC0yLjEsMTEuOGMtNS45LDE3LjItMjIuNywzNC00OS4yLDM0Yy0xOC45LDAtMzQuOS0xMS4zLTM0LjktMzUuM2MwLTM5LjUsNDUuOC00Ni42LDg2LjItNDUuOFYyNTcuN3ogTTE2OTguNSwzMjYuMiBsMS43LTMzLjZoMS4zYzE1LjEsMjYuOSwzOC43LDM4LjIsNjguMSwzOC4yYzQ1LjQsMCw5MS4yLTM2LjEsOTEuMi0xMDguOGMwLjQtNjEuNy0zNS4zLTEwMy43LTg1LjctMTAzLjcgYy0zMi44LDAtNTYuMywxNC43LTY5LjMsMzcuNGgtMC44VjI4aC0zNi42djI0NS43YzAsMTguMS0wLjgsMzguNi0xLjcsNTIuNUgxNjk4LjV6IE0xNzA0LjgsMjA4LjJjMC01LjksMS4zLTEwLjksMi4xLTE1LjEgYzcuNi0yOC4xLDMxLjEtNDUuNCw1Ni4zLTQ1LjRjMzkuNSwwLDYwLjUsMzQuOSw2MC41LDc1LjZjMCw0Ni42LTIzLjEsNzguMS02MS44LDc4LjFjLTI2LjksMC00OC4zLTE3LjYtNTUuNS00My4zIGMtMC44LTQuMi0xLjctOC44LTEuNy0xMy40VjIwOC4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzYxNjE2MSIgZD0iTTE1IDlIOXY2aDZWOXptLTIgNGgtMnYtMmgydjJ6bTgtMlY5aC0yVjdjMC0xLjEtLjktMi0yLTJoLTJWM2gtMnYyaC0yVjNIOXYySDdjLTEuMSAwLTIgLjktMiAydjJIM3YyaDJ2MkgzdjJoMnYyYzAgMS4xLjkgMiAyIDJoMnYyaDJ2LTJoMnYyaDJ2LTJoMmMxLjEgMCAyLS45IDItMnYtMmgydi0yaC0ydi0yaDJ6bS00IDZIN1Y3aDEwdjEweiIvPgo8L3N2Zz4K);
  --jp-icon-keyboard: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMTdjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY3YzAtMS4xLS45LTItMi0yem0tOSAzaDJ2MmgtMlY4em0wIDNoMnYyaC0ydi0yek04IDhoMnYySDhWOHptMCAzaDJ2Mkg4di0yem0tMSAySDV2LTJoMnYyem0wLTNINVY4aDJ2MnptOSA3SDh2LTJoOHYyem0wLTRoLTJ2LTJoMnYyem0wLTNoLTJWOGgydjJ6bTMgM2gtMnYtMmgydjJ6bTAtM2gtMlY4aDJ2MnoiLz4KPC9zdmc+Cg==);
  --jp-icon-launch: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMzIgMzIiIHdpZHRoPSIzMiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0yNiwyOEg2YTIuMDAyNywyLjAwMjcsMCwwLDEtMi0yVjZBMi4wMDI3LDIuMDAyNywwLDAsMSw2LDRIMTZWNkg2VjI2SDI2VjE2aDJWMjZBMi4wMDI3LDIuMDAyNywwLDAsMSwyNiwyOFoiLz4KICAgIDxwb2x5Z29uIHBvaW50cz0iMjAgMiAyMCA0IDI2LjU4NiA0IDE4IDEyLjU4NiAxOS40MTQgMTQgMjggNS40MTQgMjggMTIgMzAgMTIgMzAgMiAyMCAyIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-launcher: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkgMTlINVY1aDdWM0g1YTIgMiAwIDAwLTIgMnYxNGEyIDIgMCAwMDIgMmgxNGMxLjEgMCAyLS45IDItMnYtN2gtMnY3ek0xNCAzdjJoMy41OWwtOS44MyA5LjgzIDEuNDEgMS40MUwxOSA2LjQxVjEwaDJWM2gtN3oiLz4KPC9zdmc+Cg==);
  --jp-icon-line-form: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGZpbGw9IndoaXRlIiBkPSJNNS44OCA0LjEyTDEzLjc2IDEybC03Ljg4IDcuODhMOCAyMmwxMC0xMEw4IDJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-link: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMuOSAxMmMwLTEuNzEgMS4zOS0zLjEgMy4xLTMuMWg0VjdIN2MtMi43NiAwLTUgMi4yNC01IDVzMi4yNCA1IDUgNWg0di0xLjlIN2MtMS43MSAwLTMuMS0xLjM5LTMuMS0zLjF6TTggMTNoOHYtMkg4djJ6bTktNmgtNHYxLjloNGMxLjcxIDAgMy4xIDEuMzkgMy4xIDMuMXMtMS4zOSAzLjEtMy4xIDMuMWgtNFYxN2g0YzIuNzYgMCA1LTIuMjQgNS01cy0yLjI0LTUtNS01eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xOSA1djE0SDVWNWgxNG0xLjEtMkgzLjljLS41IDAtLjkuNC0uOS45djE2LjJjMCAuNC40LjkuOS45aDE2LjJjLjQgMCAuOS0uNS45LS45VjMuOWMwLS41LS41LS45LS45LS45ek0xMSA3aDZ2MmgtNlY3em0wIDRoNnYyaC02di0yem0wIDRoNnYyaC02ek03IDdoMnYySDd6bTAgNGgydjJIN3ptMCA0aDJ2Mkg3eiIvPgo8L3N2Zz4K);
  --jp-icon-markdown: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjN0IxRkEyIiBkPSJNNSAxNC45aDEybC02LjEgNnptOS40LTYuOGMwLTEuMy0uMS0yLjktLjEtNC41LS40IDEuNC0uOSAyLjktMS4zIDQuM2wtMS4zIDQuM2gtMkw4LjUgNy45Yy0uNC0xLjMtLjctMi45LTEtNC4zLS4xIDEuNi0uMSAzLjItLjIgNC42TDcgMTIuNEg0LjhsLjctMTFoMy4zTDEwIDVjLjQgMS4yLjcgMi43IDEgMy45LjMtMS4yLjctMi42IDEtMy45bDEuMi0zLjdoMy4zbC42IDExaC0yLjRsLS4zLTQuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-move-down: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBkPSJNMTIuNDcxIDcuNTI4OTlDMTIuNzYzMiA3LjIzNjg0IDEyLjc2MzIgNi43NjMxNiAxMi40NzEgNi40NzEwMVY2LjQ3MTAxQzEyLjE3OSA2LjE3OTA1IDExLjcwNTcgNi4xNzg4NCAxMS40MTM1IDYuNDcwNTRMNy43NSAxMC4xMjc1VjEuNzVDNy43NSAxLjMzNTc5IDcuNDE0MjEgMSA3IDFWMUM2LjU4NTc5IDEgNi4yNSAxLjMzNTc5IDYuMjUgMS43NVYxMC4xMjc1TDIuNTk3MjYgNi40NjgyMkMyLjMwMzM4IDYuMTczODEgMS44MjY0MSA2LjE3MzU5IDEuNTMyMjYgNi40Njc3NFY2LjQ2Nzc0QzEuMjM4MyA2Ljc2MTcgMS4yMzgzIDcuMjM4MyAxLjUzMjI2IDcuNTMyMjZMNi4yOTI4OSAxMi4yOTI5QzYuNjgzNDIgMTIuNjgzNCA3LjMxNjU4IDEyLjY4MzQgNy43MDcxMSAxMi4yOTI5TDEyLjQ3MSA3LjUyODk5WiIgZmlsbD0iIzYxNjE2MSIvPgo8L3N2Zz4K);
  --jp-icon-move-up: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBkPSJNMS41Mjg5OSA2LjQ3MTAxQzEuMjM2ODQgNi43NjMxNiAxLjIzNjg0IDcuMjM2ODQgMS41Mjg5OSA3LjUyODk5VjcuNTI4OTlDMS44MjA5NSA3LjgyMDk1IDIuMjk0MjYgNy44MjExNiAyLjU4NjQ5IDcuNTI5NDZMNi4yNSAzLjg3MjVWMTIuMjVDNi4yNSAxMi42NjQyIDYuNTg1NzkgMTMgNyAxM1YxM0M3LjQxNDIxIDEzIDcuNzUgMTIuNjY0MiA3Ljc1IDEyLjI1VjMuODcyNUwxMS40MDI3IDcuNTMxNzhDMTEuNjk2NiA3LjgyNjE5IDEyLjE3MzYgNy44MjY0MSAxMi40Njc3IDcuNTMyMjZWNy41MzIyNkMxMi43NjE3IDcuMjM4MyAxMi43NjE3IDYuNzYxNyAxMi40Njc3IDYuNDY3NzRMNy43MDcxMSAxLjcwNzExQzcuMzE2NTggMS4zMTY1OCA2LjY4MzQyIDEuMzE2NTggNi4yOTI4OSAxLjcwNzExTDEuNTI4OTkgNi40NzEwMVoiIGZpbGw9IiM2MTYxNjEiLz4KPC9zdmc+Cg==);
  --jp-icon-new-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwIDZoLThsLTItMkg0Yy0xLjExIDAtMS45OS44OS0xLjk5IDJMMiAxOGMwIDEuMTEuODkgMiAyIDJoMTZjMS4xMSAwIDItLjg5IDItMlY4YzAtMS4xMS0uODktMi0yLTJ6bS0xIDhoLTN2M2gtMnYtM2gtM3YtMmgzVjloMnYzaDN2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-not-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI1IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMTkgMTcuMTg0NCAyLjk2OTY4IDE0LjMwMzIgMS44NjA5NCAxMS40NDA5WiIvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24yIiBzdHJva2U9IiMzMzMzMzMiIHN0cm9rZS13aWR0aD0iMiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOS4zMTU5MiA5LjMyMDMxKSIgZD0iTTcuMzY4NDIgMEwwIDcuMzY0NzkiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDkuMzE1OTIgMTYuNjgzNikgc2NhbGUoMSAtMSkiIGQ9Ik03LjM2ODQyIDBMMCA3LjM2NDc5Ii8+Cjwvc3ZnPgo=);
  --jp-icon-notebook: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtbm90ZWJvb2staWNvbi1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNFRjZDMDAiPgogICAgPHBhdGggZD0iTTE4LjcgMy4zdjE1LjRIMy4zVjMuM2gxNS40bTEuNS0xLjVIMS44djE4LjNoMTguM2wuMS0xOC4zeiIvPgogICAgPHBhdGggZD0iTTE2LjUgMTYuNWwtNS40LTQuMy01LjYgNC4zdi0xMWgxMXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-numbering: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTQgMTlINlYxOS41SDVWMjAuNUg2VjIxSDRWMjJIN1YxOEg0VjE5Wk01IDEwSDZWNkg0VjdINVYxMFpNNCAxM0g1LjhMNCAxNS4xVjE2SDdWMTVINS4yTDcgMTIuOVYxMkg0VjEzWk05IDdWOUgyM1Y3SDlaTTkgMjFIMjNWMTlIOVYyMVpNOSAxNUgyM1YxM0g5VjE1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-offline-bolt: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDIuMDJjLTUuNTEgMC05Ljk4IDQuNDctOS45OCA5Ljk4czQuNDcgOS45OCA5Ljk4IDkuOTggOS45OC00LjQ3IDkuOTgtOS45OFMxNy41MSAyLjAyIDEyIDIuMDJ6TTExLjQ4IDIwdi02LjI2SDhMMTMgNHY2LjI2aDMuMzVMMTEuNDggMjB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-palette: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE4IDEzVjIwSDRWNkg5LjAyQzkuMDcgNS4yOSA5LjI0IDQuNjIgOS41IDRINEMyLjkgNCAyIDQuOSAyIDZWMjBDMiAyMS4xIDIuOSAyMiA0IDIySDE4QzE5LjEgMjIgMjAgMjEuMSAyMCAyMFYxNUwxOCAxM1pNMTkuMyA4Ljg5QzE5Ljc0IDguMTkgMjAgNy4zOCAyMCA2LjVDMjAgNC4wMSAxNy45OSAyIDE1LjUgMkMxMy4wMSAyIDExIDQuMDEgMTEgNi41QzExIDguOTkgMTMuMDEgMTEgMTUuNDkgMTFDMTYuMzcgMTEgMTcuMTkgMTAuNzQgMTcuODggMTAuM0wyMSAxMy40MkwyMi40MiAxMkwxOS4zIDguODlaTTE1LjUgOUMxNC4xMiA5IDEzIDcuODggMTMgNi41QzEzIDUuMTIgMTQuMTIgNCAxNS41IDRDMTYuODggNCAxOCA1LjEyIDE4IDYuNUMxOCA3Ljg4IDE2Ljg4IDkgMTUuNSA5WiIvPgogICAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik00IDZIOS4wMTg5NEM5LjAwNjM5IDYuMTY1MDIgOSA2LjMzMTc2IDkgNi41QzkgOC44MTU3NyAxMC4yMTEgMTAuODQ4NyAxMi4wMzQzIDEySDlWMTRIMTZWMTIuOTgxMUMxNi41NzAzIDEyLjkzNzcgMTcuMTIgMTIuODIwNyAxNy42Mzk2IDEyLjYzOTZMMTggMTNWMjBINFY2Wk04IDhINlYxMEg4VjhaTTYgMTJIOFYxNEg2VjEyWk04IDE2SDZWMThIOFYxNlpNOSAxNkgxNlYxOEg5VjE2WiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-paste: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE5IDJoLTQuMThDMTQuNC44NCAxMy4zIDAgMTIgMGMtMS4zIDAtMi40Ljg0LTIuODIgMkg1Yy0xLjEgMC0yIC45LTIgMnYxNmMwIDEuMS45IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjRjMC0xLjEtLjktMi0yLTJ6bS03IDBjLjU1IDAgMSAuNDUgMSAxcy0uNDUgMS0xIDEtMS0uNDUtMS0xIC40NS0xIDEtMXptNyAxOEg1VjRoMnYzaDEwVjRoMnYxNnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-pdf: url(data:image/svg+xml;base64,PHN2ZwogICB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyMiAyMiIgd2lkdGg9IjE2Ij4KICAgIDxwYXRoIHRyYW5zZm9ybT0icm90YXRlKDQ1KSIgY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI0ZGMkEyQSIKICAgICAgIGQ9Im0gMjIuMzQ0MzY5LC0zLjAxNjM2NDIgaCA1LjYzODYwNCB2IDEuNTc5MjQzMyBoIC0zLjU0OTIyNyB2IDEuNTA4NjkyOTkgaCAzLjMzNzU3NiBWIDEuNjUwODE1NCBoIC0zLjMzNzU3NiB2IDMuNDM1MjYxMyBoIC0yLjA4OTM3NyB6IG0gLTcuMTM2NDQ0LDEuNTc5MjQzMyB2IDQuOTQzOTU0MyBoIDAuNzQ4OTIgcSAxLjI4MDc2MSwwIDEuOTUzNzAzLC0wLjYzNDk1MzUgMC42NzgzNjksLTAuNjM0OTUzNSAwLjY3ODM2OSwtMS44NDUxNjQxIDAsLTEuMjA0NzgzNTUgLTAuNjcyOTQyLC0xLjgzNDMxMDExIC0wLjY3Mjk0MiwtMC42Mjk1MjY1OSAtMS45NTkxMywtMC42Mjk1MjY1OSB6IG0gLTIuMDg5Mzc3LC0xLjU3OTI0MzMgaCAyLjIwMzM0MyBxIDEuODQ1MTY0LDAgMi43NDYwMzksMC4yNjU5MjA3IDAuOTA2MzAxLDAuMjYwNDkzNyAxLjU1MjEwOCwwLjg5MDAyMDMgMC41Njk4MywwLjU0ODEyMjMgMC44NDY2MDUsMS4yNjQ0ODAwNiAwLjI3Njc3NCwwLjcxNjM1NzgxIDAuMjc2Nzc0LDEuNjIyNjU4OTQgMCwwLjkxNzE1NTEgLTAuMjc2Nzc0LDEuNjM4OTM5OSAtMC4yNzY3NzUsMC43MTYzNTc4IC0wLjg0NjYwNSwxLjI2NDQ4IC0wLjY1MTIzNCwwLjYyOTUyNjYgLTEuNTYyOTYyLDAuODk1NDQ3MyAtMC45MTE3MjgsMC4yNjA0OTM3IC0yLjczNTE4NSwwLjI2MDQ5MzcgaCAtMi4yMDMzNDMgeiBtIC04LjE0NTg1NjUsMCBoIDMuNDY3ODIzIHEgMS41NDY2ODE2LDAgMi4zNzE1Nzg1LDAuNjg5MjIzIDAuODMwMzI0LDAuNjgzNzk2MSAwLjgzMDMyNCwxLjk1MzcwMzE0IDAsMS4yNzUzMzM5NyAtMC44MzAzMjQsMS45NjQ1NTcwNiBRIDkuOTg3MTk2MSwyLjI3NDkxNSA4LjQ0MDUxNDUsMi4yNzQ5MTUgSCA3LjA2MjA2ODQgViA1LjA4NjA3NjcgSCA0Ljk3MjY5MTUgWiBtIDIuMDg5Mzc2OSwxLjUxNDExOTkgdiAyLjI2MzAzOTQzIGggMS4xNTU5NDEgcSAwLjYwNzgxODgsMCAwLjkzODg2MjksLTAuMjkzMDU1NDcgMC4zMzEwNDQxLC0wLjI5ODQ4MjQxIDAuMzMxMDQ0MSwtMC44NDExNzc3MiAwLC0wLjU0MjY5NTMxIC0wLjMzMTA0NDEsLTAuODM1NzUwNzQgLTAuMzMxMDQ0MSwtMC4yOTMwNTU1IC0wLjkzODg2MjksLTAuMjkzMDU1NSB6IgovPgo8L3N2Zz4K);
  --jp-icon-python: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iLTEwIC0xMCAxMzEuMTYxMzYxNjk0MzM1OTQgMTMyLjM4ODk5OTkzODk2NDg0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMzA2OTk4IiBkPSJNIDU0LjkxODc4NSw5LjE5Mjc0MjFlLTQgQyA1MC4zMzUxMzIsMC4wMjIyMTcyNyA0NS45NTc4NDYsMC40MTMxMzY5NyA0Mi4xMDYyODUsMS4wOTQ2NjkzIDMwLjc2MDA2OSwzLjA5OTE3MzEgMjguNzAwMDM2LDcuMjk0NzcxNCAyOC43MDAwMzUsMTUuMDMyMTY5IHYgMTAuMjE4NzUgaCAyNi44MTI1IHYgMy40MDYyNSBoIC0yNi44MTI1IC0xMC4wNjI1IGMgLTcuNzkyNDU5LDAgLTE0LjYxNTc1ODgsNC42ODM3MTcgLTE2Ljc0OTk5OTgsMTMuNTkzNzUgLTIuNDYxODE5OTgsMTAuMjEyOTY2IC0yLjU3MTAxNTA4LDE2LjU4NjAyMyAwLDI3LjI1IDEuOTA1OTI4Myw3LjkzNzg1MiA2LjQ1NzU0MzIsMTMuNTkzNzQ4IDE0LjI0OTk5OTgsMTMuNTkzNzUgaCA5LjIxODc1IHYgLTEyLjI1IGMgMCwtOC44NDk5MDIgNy42NTcxNDQsLTE2LjY1NjI0OCAxNi43NSwtMTYuNjU2MjUgaCAyNi43ODEyNSBjIDcuNDU0OTUxLDAgMTMuNDA2MjUzLC02LjEzODE2NCAxMy40MDYyNSwtMTMuNjI1IHYgLTI1LjUzMTI1IGMgMCwtNy4yNjYzMzg2IC02LjEyOTk4LC0xMi43MjQ3NzcxIC0xMy40MDYyNSwtMTMuOTM3NDk5NyBDIDY0LjI4MTU0OCwwLjMyNzk0Mzk3IDU5LjUwMjQzOCwtMC4wMjAzNzkwMyA1NC45MTg3ODUsOS4xOTI3NDIxZS00IFogbSAtMTQuNSw4LjIxODc1MDEyNTc5IGMgMi43Njk1NDcsMCA1LjAzMTI1LDIuMjk4NjQ1NiA1LjAzMTI1LDUuMTI0OTk5NiAtMmUtNiwyLjgxNjMzNiAtMi4yNjE3MDMsNS4wOTM3NSAtNS4wMzEyNSw1LjA5Mzc1IC0yLjc3OTQ3NiwtMWUtNiAtNS4wMzEyNSwtMi4yNzc0MTUgLTUuMDMxMjUsLTUuMDkzNzUgLTEwZS03LC0yLjgyNjM1MyAyLjI1MTc3NCwtNS4xMjQ5OTk2IDUuMDMxMjUsLTUuMTI0OTk5NiB6Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI2ZmZDQzYiIgZD0ibSA4NS42Mzc1MzUsMjguNjU3MTY5IHYgMTEuOTA2MjUgYyAwLDkuMjMwNzU1IC03LjgyNTg5NSwxNi45OTk5OTkgLTE2Ljc1LDE3IGggLTI2Ljc4MTI1IGMgLTcuMzM1ODMzLDAgLTEzLjQwNjI0OSw2LjI3ODQ4MyAtMTMuNDA2MjUsMTMuNjI1IHYgMjUuNTMxMjQ3IGMgMCw3LjI2NjM0NCA2LjMxODU4OCwxMS41NDAzMjQgMTMuNDA2MjUsMTMuNjI1MDA0IDguNDg3MzMxLDIuNDk1NjEgMTYuNjI2MjM3LDIuOTQ2NjMgMjYuNzgxMjUsMCA2Ljc1MDE1NSwtMS45NTQzOSAxMy40MDYyNTMsLTUuODg3NjEgMTMuNDA2MjUsLTEzLjYyNTAwNCBWIDg2LjUwMDkxOSBoIC0yNi43ODEyNSB2IC0zLjQwNjI1IGggMjYuNzgxMjUgMTMuNDA2MjU0IGMgNy43OTI0NjEsMCAxMC42OTYyNTEsLTUuNDM1NDA4IDEzLjQwNjI0MSwtMTMuNTkzNzUgMi43OTkzMywtOC4zOTg4ODYgMi42ODAyMiwtMTYuNDc1Nzc2IDAsLTI3LjI1IC0xLjkyNTc4LC03Ljc1NzQ0MSAtNS42MDM4NywtMTMuNTkzNzUgLTEzLjQwNjI0MSwtMTMuNTkzNzUgeiBtIC0xNS4wNjI1LDY0LjY1NjI1IGMgMi43Nzk0NzgsM2UtNiA1LjAzMTI1LDIuMjc3NDE3IDUuMDMxMjUsNS4wOTM3NDcgLTJlLTYsMi44MjYzNTQgLTIuMjUxNzc1LDUuMTI1MDA0IC01LjAzMTI1LDUuMTI1MDA0IC0yLjc2OTU1LDAgLTUuMDMxMjUsLTIuMjk4NjUgLTUuMDMxMjUsLTUuMTI1MDA0IDJlLTYsLTIuODE2MzMgMi4yNjE2OTcsLTUuMDkzNzQ3IDUuMDMxMjUsLTUuMDkzNzQ3IHoiLz4KPC9zdmc+Cg==);
  --jp-icon-r-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjE5NkYzIiBkPSJNNC40IDIuNWMxLjItLjEgMi45LS4zIDQuOS0uMyAyLjUgMCA0LjEuNCA1LjIgMS4zIDEgLjcgMS41IDEuOSAxLjUgMy41IDAgMi0xLjQgMy41LTIuOSA0LjEgMS4yLjQgMS43IDEuNiAyLjIgMyAuNiAxLjkgMSAzLjkgMS4zIDQuNmgtMy44Yy0uMy0uNC0uOC0xLjctMS4yLTMuN3MtMS4yLTIuNi0yLjYtMi42aC0uOXY2LjRINC40VjIuNXptMy43IDYuOWgxLjRjMS45IDAgMi45LS45IDIuOS0yLjNzLTEtMi4zLTIuOC0yLjNjLS43IDAtMS4zIDAtMS42LjJ2NC41aC4xdi0uMXoiLz4KPC9zdmc+Cg==);
  --jp-icon-react: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMTUwIDE1MCA1NDEuOSAyOTUuMyI+CiAgPGcgY2xhc3M9ImpwLWljb24tYnJhbmQyIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxREFGQiI+CiAgICA8cGF0aCBkPSJNNjY2LjMgMjk2LjVjMC0zMi41LTQwLjctNjMuMy0xMDMuMS04Mi40IDE0LjQtNjMuNiA4LTExNC4yLTIwLjItMTMwLjQtNi41LTMuOC0xNC4xLTUuNi0yMi40LTUuNnYyMi4zYzQuNiAwIDguMy45IDExLjQgMi42IDEzLjYgNy44IDE5LjUgMzcuNSAxNC45IDc1LjctMS4xIDkuNC0yLjkgMTkuMy01LjEgMjkuNC0xOS42LTQuOC00MS04LjUtNjMuNS0xMC45LTEzLjUtMTguNS0yNy41LTM1LjMtNDEuNi01MCAzMi42LTMwLjMgNjMuMi00Ni45IDg0LTQ2LjlWNzhjLTI3LjUgMC02My41IDE5LjYtOTkuOSA1My42LTM2LjQtMzMuOC03Mi40LTUzLjItOTkuOS01My4ydjIyLjNjMjAuNyAwIDUxLjQgMTYuNSA4NCA0Ni42LTE0IDE0LjctMjggMzEuNC00MS4zIDQ5LjktMjIuNiAyLjQtNDQgNi4xLTYzLjYgMTEtMi4zLTEwLTQtMTkuNy01LjItMjktNC43LTM4LjIgMS4xLTY3LjkgMTQuNi03NS44IDMtMS44IDYuOS0yLjYgMTEuNS0yLjZWNzguNWMtOC40IDAtMTYgMS44LTIyLjYgNS42LTI4LjEgMTYuMi0zNC40IDY2LjctMTkuOSAxMzAuMS02Mi4yIDE5LjItMTAyLjcgNDkuOS0xMDIuNyA4Mi4zIDAgMzIuNSA0MC43IDYzLjMgMTAzLjEgODIuNC0xNC40IDYzLjYtOCAxMTQuMiAyMC4yIDEzMC40IDYuNSAzLjggMTQuMSA1LjYgMjIuNSA1LjYgMjcuNSAwIDYzLjUtMTkuNiA5OS45LTUzLjYgMzYuNCAzMy44IDcyLjQgNTMuMiA5OS45IDUzLjIgOC40IDAgMTYtMS44IDIyLjYtNS42IDI4LjEtMTYuMiAzNC40LTY2LjcgMTkuOS0xMzAuMSA2Mi0xOS4xIDEwMi41LTQ5LjkgMTAyLjUtODIuM3ptLTEzMC4yLTY2LjdjLTMuNyAxMi45LTguMyAyNi4yLTEzLjUgMzkuNS00LjEtOC04LjQtMTYtMTMuMS0yNC00LjYtOC05LjUtMTUuOC0xNC40LTIzLjQgMTQuMiAyLjEgMjcuOSA0LjcgNDEgNy45em0tNDUuOCAxMDYuNWMtNy44IDEzLjUtMTUuOCAyNi4zLTI0LjEgMzguMi0xNC45IDEuMy0zMCAyLTQ1LjIgMi0xNS4xIDAtMzAuMi0uNy00NS0xLjktOC4zLTExLjktMTYuNC0yNC42LTI0LjItMzgtNy42LTEzLjEtMTQuNS0yNi40LTIwLjgtMzkuOCA2LjItMTMuNCAxMy4yLTI2LjggMjAuNy0zOS45IDcuOC0xMy41IDE1LjgtMjYuMyAyNC4xLTM4LjIgMTQuOS0xLjMgMzAtMiA0NS4yLTIgMTUuMSAwIDMwLjIuNyA0NSAxLjkgOC4zIDExLjkgMTYuNCAyNC42IDI0LjIgMzggNy42IDEzLjEgMTQuNSAyNi40IDIwLjggMzkuOC02LjMgMTMuNC0xMy4yIDI2LjgtMjAuNyAzOS45em0zMi4zLTEzYzUuNCAxMy40IDEwIDI2LjggMTMuOCAzOS44LTEzLjEgMy4yLTI2LjkgNS45LTQxLjIgOCA0LjktNy43IDkuOC0xNS42IDE0LjQtMjMuNyA0LjYtOCA4LjktMTYuMSAxMy0yNC4xek00MjEuMiA0MzBjLTkuMy05LjYtMTguNi0yMC4zLTI3LjgtMzIgOSAuNCAxOC4yLjcgMjcuNS43IDkuNCAwIDE4LjctLjIgMjcuOC0uNy05IDExLjctMTguMyAyMi40LTI3LjUgMzJ6bS03NC40LTU4LjljLTE0LjItMi4xLTI3LjktNC43LTQxLTcuOSAzLjctMTIuOSA4LjMtMjYuMiAxMy41LTM5LjUgNC4xIDggOC40IDE2IDEzLjEgMjQgNC43IDggOS41IDE1LjggMTQuNCAyMy40ek00MjAuNyAxNjNjOS4zIDkuNiAxOC42IDIwLjMgMjcuOCAzMi05LS40LTE4LjItLjctMjcuNS0uNy05LjQgMC0xOC43LjItMjcuOC43IDktMTEuNyAxOC4zLTIyLjQgMjcuNS0zMnptLTc0IDU4LjljLTQuOSA3LjctOS44IDE1LjYtMTQuNCAyMy43LTQuNiA4LTguOSAxNi0xMyAyNC01LjQtMTMuNC0xMC0yNi44LTEzLjgtMzkuOCAxMy4xLTMuMSAyNi45LTUuOCA0MS4yLTcuOXptLTkwLjUgMTI1LjJjLTM1LjQtMTUuMS01OC4zLTM0LjktNTguMy01MC42IDAtMTUuNyAyMi45LTM1LjYgNTguMy01MC42IDguNi0zLjcgMTgtNyAyNy43LTEwLjEgNS43IDE5LjYgMTMuMiA0MCAyMi41IDYwLjktOS4yIDIwLjgtMTYuNiA0MS4xLTIyLjIgNjAuNi05LjktMy4xLTE5LjMtNi41LTI4LTEwLjJ6TTMxMCA0OTBjLTEzLjYtNy44LTE5LjUtMzcuNS0xNC45LTc1LjcgMS4xLTkuNCAyLjktMTkuMyA1LjEtMjkuNCAxOS42IDQuOCA0MSA4LjUgNjMuNSAxMC45IDEzLjUgMTguNSAyNy41IDM1LjMgNDEuNiA1MC0zMi42IDMwLjMtNjMuMiA0Ni45LTg0IDQ2LjktNC41LS4xLTguMy0xLTExLjMtMi43em0yMzcuMi03Ni4yYzQuNyAzOC4yLTEuMSA2Ny45LTE0LjYgNzUuOC0zIDEuOC02LjkgMi42LTExLjUgMi42LTIwLjcgMC01MS40LTE2LjUtODQtNDYuNiAxNC0xNC43IDI4LTMxLjQgNDEuMy00OS45IDIyLjYtMi40IDQ0LTYuMSA2My42LTExIDIuMyAxMC4xIDQuMSAxOS44IDUuMiAyOS4xem0zOC41LTY2LjdjLTguNiAzLjctMTggNy0yNy43IDEwLjEtNS43LTE5LjYtMTMuMi00MC0yMi41LTYwLjkgOS4yLTIwLjggMTYuNi00MS4xIDIyLjItNjAuNiA5LjkgMy4xIDE5LjMgNi41IDI4LjEgMTAuMiAzNS40IDE1LjEgNTguMyAzNC45IDU4LjMgNTAuNi0uMSAxNS43LTIzIDM1LjYtNTguNCA1MC42ek0zMjAuOCA3OC40eiIvPgogICAgPGNpcmNsZSBjeD0iNDIwLjkiIGN5PSIyOTYuNSIgcj0iNDUuNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-redo: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PHBhdGggZD0iTTE4LjQgMTAuNkMxNi41NSA4Ljk5IDE0LjE1IDggMTEuNSA4Yy00LjY1IDAtOC41OCAzLjAzLTkuOTYgNy4yMkwzLjkgMTZjMS4wNS0zLjE5IDQuMDUtNS41IDcuNi01LjUgMS45NSAwIDMuNzMuNzIgNS4xMiAxLjg4TDEzIDE2aDlWN2wtMy42IDMuNnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-refresh: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTkgMTMuNWMtMi40OSAwLTQuNS0yLjAxLTQuNS00LjVTNi41MSA0LjUgOSA0LjVjMS4yNCAwIDIuMzYuNTIgMy4xNyAxLjMzTDEwIDhoNVYzbC0xLjc2IDEuNzZDMTIuMTUgMy42OCAxMC42NiAzIDkgMyA1LjY5IDMgMy4wMSA1LjY5IDMuMDEgOVM1LjY5IDE1IDkgMTVjMi45NyAwIDUuNDMtMi4xNiA1LjktNWgtMS41MmMtLjQ2IDItMi4yNCAzLjUtNC4zOCAzLjV6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-regex: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi1hY2NlbnQyIiBmaWxsPSIjRkZGIj4KICAgIDxjaXJjbGUgY2xhc3M9InN0MiIgY3g9IjUuNSIgY3k9IjE0LjUiIHI9IjEuNSIvPgogICAgPHJlY3QgeD0iMTIiIHk9IjQiIGNsYXNzPSJzdDIiIHdpZHRoPSIxIiBoZWlnaHQ9IjgiLz4KICAgIDxyZWN0IHg9IjguNSIgeT0iNy41IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjg2NiAtMC41IDAuNSAwLjg2NiAtMi4zMjU1IDcuMzIxOSkiIGNsYXNzPSJzdDIiIHdpZHRoPSI4IiBoZWlnaHQ9IjEiLz4KICAgIDxyZWN0IHg9IjEyIiB5PSI0IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjUgLTAuODY2IDAuODY2IDAuNSAtMC42Nzc5IDE0LjgyNTIpIiBjbGFzcz0ic3QyIiB3aWR0aD0iMSIgaGVpZ2h0PSI4Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-run: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTggNXYxNGwxMS03eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-running: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMjU2IDhDMTE5IDggOCAxMTkgOCAyNTZzMTExIDI0OCAyNDggMjQ4IDI0OC0xMTEgMjQ4LTI0OFMzOTMgOCAyNTYgOHptOTYgMzI4YzAgOC44LTcuMiAxNi0xNiAxNkgxNzZjLTguOCAwLTE2LTcuMi0xNi0xNlYxNzZjMC04LjggNy4yLTE2IDE2LTE2aDE2MGM4LjggMCAxNiA3LjIgMTYgMTZ2MTYweiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-save: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE3IDNINWMtMS4xMSAwLTIgLjktMiAydjE0YzAgMS4xLjg5IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjdsLTQtNHptLTUgMTZjLTEuNjYgMC0zLTEuMzQtMy0zczEuMzQtMyAzLTMgMyAxLjM0IDMgMy0xLjM0IDMtMyAzem0zLTEwSDVWNWgxMHY0eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-search: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjEsMTAuOWgtMC43bC0wLjItMC4yYzAuOC0wLjksMS4zLTIuMiwxLjMtMy41YzAtMy0yLjQtNS40LTUuNC01LjRTMS44LDQuMiwxLjgsNy4xczIuNCw1LjQsNS40LDUuNCBjMS4zLDAsMi41LTAuNSwzLjUtMS4zbDAuMiwwLjJ2MC43bDQuMSw0LjFsMS4yLTEuMkwxMi4xLDEwLjl6IE03LjEsMTAuOWMtMi4xLDAtMy43LTEuNy0zLjctMy43czEuNy0zLjcsMy43LTMuN3MzLjcsMS43LDMuNywzLjcgUzkuMiwxMC45LDcuMSwxMC45eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-settings: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuNDMgMTIuOThjLjA0LS4zMi4wNy0uNjQuMDctLjk4cy0uMDMtLjY2LS4wNy0uOThsMi4xMS0xLjY1Yy4xOS0uMTUuMjQtLjQyLjEyLS42NGwtMi0zLjQ2Yy0uMTItLjIyLS4zOS0uMy0uNjEtLjIybC0yLjQ5IDFjLS41Mi0uNC0xLjA4LS43My0xLjY5LS45OGwtLjM4LTIuNjVBLjQ4OC40ODggMCAwMDE0IDJoLTRjLS4yNSAwLS40Ni4xOC0uNDkuNDJsLS4zOCAyLjY1Yy0uNjEuMjUtMS4xNy41OS0xLjY5Ljk4bC0yLjQ5LTFjLS4yMy0uMDktLjQ5IDAtLjYxLjIybC0yIDMuNDZjLS4xMy4yMi0uMDcuNDkuMTIuNjRsMi4xMSAxLjY1Yy0uMDQuMzItLjA3LjY1LS4wNy45OHMuMDMuNjYuMDcuOThsLTIuMTEgMS42NWMtLjE5LjE1LS4yNC40Mi0uMTIuNjRsMiAzLjQ2Yy4xMi4yMi4zOS4zLjYxLjIybDIuNDktMWMuNTIuNCAxLjA4LjczIDEuNjkuOThsLjM4IDIuNjVjLjAzLjI0LjI0LjQyLjQ5LjQyaDRjLjI1IDAgLjQ2LS4xOC40OS0uNDJsLjM4LTIuNjVjLjYxLS4yNSAxLjE3LS41OSAxLjY5LS45OGwyLjQ5IDFjLjIzLjA5LjQ5IDAgLjYxLS4yMmwyLTMuNDZjLjEyLS4yMi4wNy0uNDktLjEyLS42NGwtMi4xMS0xLjY1ek0xMiAxNS41Yy0xLjkzIDAtMy41LTEuNTctMy41LTMuNXMxLjU3LTMuNSAzLjUtMy41IDMuNSAxLjU3IDMuNSAzLjUtMS41NyAzLjUtMy41IDMuNXoiLz4KPC9zdmc+Cg==);
  --jp-icon-share: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTSAxOCAyIEMgMTYuMzU0OTkgMiAxNSAzLjM1NDk5MDQgMTUgNSBDIDE1IDUuMTkwOTUyOSAxNS4wMjE3OTEgNS4zNzcxMjI0IDE1LjA1NjY0MSA1LjU1ODU5MzggTCA3LjkyMTg3NSA5LjcyMDcwMzEgQyA3LjM5ODUzOTkgOS4yNzc4NTM5IDYuNzMyMDc3MSA5IDYgOSBDIDQuMzU0OTkwNCA5IDMgMTAuMzU0OTkgMyAxMiBDIDMgMTMuNjQ1MDEgNC4zNTQ5OTA0IDE1IDYgMTUgQyA2LjczMjA3NzEgMTUgNy4zOTg1Mzk5IDE0LjcyMjE0NiA3LjkyMTg3NSAxNC4yNzkyOTcgTCAxNS4wNTY2NDEgMTguNDM5NDUzIEMgMTUuMDIxNTU1IDE4LjYyMTUxNCAxNSAxOC44MDgzODYgMTUgMTkgQyAxNSAyMC42NDUwMSAxNi4zNTQ5OSAyMiAxOCAyMiBDIDE5LjY0NTAxIDIyIDIxIDIwLjY0NTAxIDIxIDE5IEMgMjEgMTcuMzU0OTkgMTkuNjQ1MDEgMTYgMTggMTYgQyAxNy4yNjc0OCAxNiAxNi42MDE1OTMgMTYuMjc5MzI4IDE2LjA3ODEyNSAxNi43MjI2NTYgTCA4Ljk0MzM1OTQgMTIuNTU4NTk0IEMgOC45NzgyMDk1IDEyLjM3NzEyMiA5IDEyLjE5MDk1MyA5IDEyIEMgOSAxMS44MDkwNDcgOC45NzgyMDk1IDExLjYyMjg3OCA4Ljk0MzM1OTQgMTEuNDQxNDA2IEwgMTYuMDc4MTI1IDcuMjc5Mjk2OSBDIDE2LjYwMTQ2IDcuNzIyMTQ2MSAxNy4yNjc5MjMgOCAxOCA4IEMgMTkuNjQ1MDEgOCAyMSA2LjY0NTAwOTYgMjEgNSBDIDIxIDMuMzU0OTkwNCAxOS42NDUwMSAyIDE4IDIgeiBNIDE4IDQgQyAxOC41NjQxMjkgNCAxOSA0LjQzNTg3MDYgMTkgNSBDIDE5IDUuNTY0MTI5NCAxOC41NjQxMjkgNiAxOCA2IEMgMTcuNDM1ODcxIDYgMTcgNS41NjQxMjk0IDE3IDUgQyAxNyA0LjQzNTg3MDYgMTcuNDM1ODcxIDQgMTggNCB6IE0gNiAxMSBDIDYuNTY0MTI5NCAxMSA3IDExLjQzNTg3MSA3IDEyIEMgNyAxMi41NjQxMjkgNi41NjQxMjk0IDEzIDYgMTMgQyA1LjQzNTg3MDYgMTMgNSAxMi41NjQxMjkgNSAxMiBDIDUgMTEuNDM1ODcxIDUuNDM1ODcwNiAxMSA2IDExIHogTSAxOCAxOCBDIDE4LjU2NDEyOSAxOCAxOSAxOC40MzU4NzEgMTkgMTkgQyAxOSAxOS41NjQxMjkgMTguNTY0MTI5IDIwIDE4IDIwIEMgMTcuNDM1ODcxIDIwIDE3IDE5LjU2NDEyOSAxNyAxOSBDIDE3IDE4LjQzNTg3MSAxNy40MzU4NzEgMTggMTggMTggeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-spreadsheet: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNENBRjUwIiBkPSJNMi4yIDIuMnYxNy42aDE3LjZWMi4ySDIuMnptMTUuNCA3LjdoLTUuNVY0LjRoNS41djUuNXpNOS45IDQuNHY1LjVINC40VjQuNGg1LjV6bS01LjUgNy43aDUuNXY1LjVINC40di01LjV6bTcuNyA1LjV2LTUuNWg1LjV2NS41aC01LjV6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-stop: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik02IDZoMTJ2MTJINnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tab: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIxIDNIM2MtMS4xIDAtMiAuOS0yIDJ2MTRjMCAxLjEuOSAyIDIgMmgxOGMxLjEgMCAyLS45IDItMlY1YzAtMS4xLS45LTItMi0yem0wIDE2SDNWNWgxMHY0aDh2MTB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-table-rows: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMSw4SDNWNGgxOFY4eiBNMjEsMTBIM3Y0aDE4VjEweiBNMjEsMTZIM3Y0aDE4VjE2eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-tag: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjgiIGhlaWdodD0iMjgiIHZpZXdCb3g9IjAgMCA0MyAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTI4LjgzMzIgMTIuMzM0TDMyLjk5OTggMTYuNTAwN0wzNy4xNjY1IDEyLjMzNEgyOC44MzMyWiIvPgoJCTxwYXRoIGQ9Ik0xNi4yMDk1IDIxLjYxMDRDMTUuNjg3MyAyMi4xMjk5IDE0Ljg0NDMgMjIuMTI5OSAxNC4zMjQ4IDIxLjYxMDRMNi45ODI5IDE0LjcyNDVDNi41NzI0IDE0LjMzOTQgNi4wODMxMyAxMy42MDk4IDYuMDQ3ODYgMTMuMDQ4MkM1Ljk1MzQ3IDExLjUyODggNi4wMjAwMiA4LjYxOTQ0IDYuMDY2MjEgNy4wNzY5NUM2LjA4MjgxIDYuNTE0NzcgNi41NTU0OCA2LjA0MzQ3IDcuMTE4MDQgNi4wMzA1NUM5LjA4ODYzIDUuOTg0NzMgMTMuMjYzOCA1LjkzNTc5IDEzLjY1MTggNi4zMjQyNUwyMS43MzY5IDEzLjYzOUMyMi4yNTYgMTQuMTU4NSAyMS43ODUxIDE1LjQ3MjQgMjEuMjYyIDE1Ljk5NDZMMTYuMjA5NSAyMS42MTA0Wk05Ljc3NTg1IDguMjY1QzkuMzM1NTEgNy44MjU2NiA4LjYyMzUxIDcuODI1NjYgOC4xODI4IDguMjY1QzcuNzQzNDYgOC43MDU3MSA3Ljc0MzQ2IDkuNDE3MzMgOC4xODI4IDkuODU2NjdDOC42MjM4MiAxMC4yOTY0IDkuMzM1ODIgMTAuMjk2NCA5Ljc3NTg1IDkuODU2NjdDMTAuMjE1NiA5LjQxNzMzIDEwLjIxNTYgOC43MDUzMyA5Ljc3NTg1IDguMjY1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-terminal: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0IiA+CiAgICA8cmVjdCBjbGFzcz0ianAtdGVybWluYWwtaWNvbi1iYWNrZ3JvdW5kLWNvbG9yIGpwLWljb24tc2VsZWN0YWJsZSIgd2lkdGg9IjIwIiBoZWlnaHQ9IjIwIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgyIDIpIiBmaWxsPSIjMzMzMzMzIi8+CiAgICA8cGF0aCBjbGFzcz0ianAtdGVybWluYWwtaWNvbi1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUtaW52ZXJzZSIgZD0iTTUuMDU2NjQgOC43NjE3MkM1LjA1NjY0IDguNTk3NjYgNS4wMzEyNSA4LjQ1MzEyIDQuOTgwNDcgOC4zMjgxMkM0LjkzMzU5IDguMTk5MjIgNC44NTU0NyA4LjA4MjAzIDQuNzQ2MDkgNy45NzY1NkM0LjY0MDYyIDcuODcxMDkgNC41IDcuNzc1MzkgNC4zMjQyMiA3LjY4OTQ1QzQuMTUyMzQgNy41OTk2MSAzLjk0MzM2IDcuNTExNzIgMy42OTcyNyA3LjQyNTc4QzMuMzAyNzMgNy4yODUxNiAyLjk0MzM2IDcuMTM2NzIgMi42MTkxNCA2Ljk4MDQ3QzIuMjk0OTIgNi44MjQyMiAyLjAxNzU4IDYuNjQyNTggMS43ODcxMSA2LjQzNTU1QzEuNTYwNTUgNi4yMjg1MiAxLjM4NDc3IDUuOTg4MjggMS4yNTk3NyA1LjcxNDg0QzEuMTM0NzcgNS40Mzc1IDEuMDcyMjcgNS4xMDkzOCAxLjA3MjI3IDQuNzMwNDdDMS4wNzIyNyA0LjM5ODQ0IDEuMTI4OTEgNC4wOTU3IDEuMjQyMTkgMy44MjIyN0MxLjM1NTQ3IDMuNTQ0OTIgMS41MTU2MiAzLjMwNDY5IDEuNzIyNjYgMy4xMDE1NkMxLjkyOTY5IDIuODk4NDQgMi4xNzk2OSAyLjczNDM3IDIuNDcyNjYgMi42MDkzOEMyLjc2NTYyIDIuNDg0MzggMy4wOTE4IDIuNDA0MyAzLjQ1MTE3IDIuMzY5MTRWMS4xMDkzOEg0LjM4ODY3VjIuMzgwODZDNC43NDAyMyAyLjQyNzczIDUuMDU2NjQgMi41MjM0NCA1LjMzNzg5IDIuNjY3OTdDNS42MTkxNCAyLjgxMjUgNS44NTc0MiAzLjAwMTk1IDYuMDUyNzMgMy4yMzYzM0M2LjI1MTk1IDMuNDY2OCA2LjQwNDMgMy43NDAyMyA2LjUwOTc3IDQuMDU2NjRDNi42MTkxNCA0LjM2OTE0IDYuNjczODMgNC43MjA3IDYuNjczODMgNS4xMTEzM0g1LjA0NDkyQzUuMDQ0OTIgNC42Mzg2NyA0LjkzNzUgNC4yODEyNSA0LjcyMjY2IDQuMDM5MDZDNC41MDc4MSAzLjc5Mjk3IDQuMjE2OCAzLjY2OTkyIDMuODQ5NjEgMy42Njk5MkMzLjY1MDM5IDMuNjY5OTIgMy40NzY1NiAzLjY5NzI3IDMuMzI4MTIgMy43NTE5NUMzLjE4MzU5IDMuODAyNzMgMy4wNjQ0NSAzLjg3Njk1IDIuOTcwNyAzLjk3NDYxQzIuODc2OTUgNC4wNjgzNiAyLjgwNjY0IDQuMTc5NjkgMi43NTk3NyA0LjMwODU5QzIuNzE2OCA0LjQzNzUgMi42OTUzMSA0LjU3ODEyIDIuNjk1MzEgNC43MzA0N0MyLjY5NTMxIDQuODgyODEgMi43MTY4IDUuMDE5NTMgMi43NTk3NyA1LjE0MDYyQzIuODA2NjQgNS4yNTc4MSAyLjg4MjgxIDUuMzY3MTkgMi45ODgyOCA1LjQ2ODc1QzMuMDk3NjYgNS41NzAzMSAzLjI0MDIzIDUuNjY3OTcgMy40MTYwMiA1Ljc2MTcyQzMuNTkxOCA1Ljg1MTU2IDMuODEwNTUgNS45NDMzNiA0LjA3MjI3IDYuMDM3MTFDNC40NjY4IDYuMTg1NTUgNC44MjQyMiA2LjMzOTg0IDUuMTQ0NTMgNi41QzUuNDY0ODQgNi42NTYyNSA1LjczODI4IDYuODM5ODQgNS45NjQ4NCA3LjA1MDc4QzYuMTk1MzEgNy4yNTc4MSA2LjM3MTA5IDcuNSA2LjQ5MjE5IDcuNzc3MzRDNi42MTcxOSA4LjA1MDc4IDYuNjc5NjkgOC4zNzUgNi42Nzk2OSA4Ljc1QzYuNjc5NjkgOS4wOTM3NSA2LjYyMzA1IDkuNDA0MyA2LjUwOTc3IDkuNjgxNjRDNi4zOTY0OCA5Ljk1NTA4IDYuMjM0MzggMTAuMTkxNCA2LjAyMzQ0IDEwLjM5MDZDNS44MTI1IDEwLjU4OTggNS41NTg1OSAxMC43NSA1LjI2MTcyIDEwLjg3MTFDNC45NjQ4NCAxMC45ODgzIDQuNjMyODEgMTEuMDY0NSA0LjI2NTYyIDExLjA5OTZWMTIuMjQ4SDMuMzMzOThWMTEuMDk5NkMzLjAwMTk1IDExLjA2ODQgMi42Nzk2OSAxMC45OTYxIDIuMzY3MTkgMTAuODgyOEMyLjA1NDY5IDEwLjc2NTYgMS43NzczNCAxMC41OTc3IDEuNTM1MTYgMTAuMzc4OUMxLjI5Njg4IDEwLjE2MDIgMS4xMDU0NyA5Ljg4NDc3IDAuOTYwOTM4IDkuNTUyNzNDMC44MTY0MDYgOS4yMTY4IDAuNzQ0MTQxIDguODE0NDUgMC43NDQxNDEgOC4zNDU3SDIuMzc4OTFDMi4zNzg5MSA4LjYyNjk1IDIuNDE5OTIgOC44NjMyOCAyLjUwMTk1IDkuMDU0NjlDMi41ODM5OCA5LjI0MjE5IDIuNjg5NDUgOS4zOTI1OCAyLjgxODM2IDkuNTA1ODZDMi45NTExNyA5LjYxNTIzIDMuMTAxNTYgOS42OTMzNiAzLjI2OTUzIDkuNzQwMjNDMy40Mzc1IDkuNzg3MTEgMy42MDkzOCA5LjgxMDU1IDMuNzg1MTYgOS44MTA1NUM0LjIwMzEyIDkuODEwNTUgNC41MTk1MyA5LjcxMjg5IDQuNzM0MzggOS41MTc1OEM0Ljk0OTIyIDkuMzIyMjcgNS4wNTY2NCA5LjA3MDMxIDUuMDU2NjQgOC43NjE3MlpNMTMuNDE4IDEyLjI3MTVIOC4wNzQyMlYxMUgxMy40MThWMTIuMjcxNVoiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMuOTUyNjQgNikiIGZpbGw9IndoaXRlIi8+Cjwvc3ZnPgo=);
  --jp-icon-text-editor: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtdGV4dC1lZGl0b3ItaWNvbi1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xNSAxNUgzdjJoMTJ2LTJ6bTAtOEgzdjJoMTJWN3pNMyAxM2gxOHYtMkgzdjJ6bTAgOGgxOHYtMkgzdjJ6TTMgM3YyaDE4VjNIM3oiLz4KPC9zdmc+Cg==);
  --jp-icon-toc: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik03LDVIMjFWN0g3VjVNNywxM1YxMUgyMVYxM0g3TTQsNC41QTEuNSwxLjUgMCAwLDEgNS41LDZBMS41LDEuNSAwIDAsMSA0LDcuNUExLjUsMS41IDAgMCwxIDIuNSw2QTEuNSwxLjUgMCAwLDEgNCw0LjVNNCwxMC41QTEuNSwxLjUgMCAwLDEgNS41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMy41QTEuNSwxLjUgMCAwLDEgMi41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMC41TTcsMTlWMTdIMjFWMTlIN000LDE2LjVBMS41LDEuNSAwIDAsMSA1LjUsMThBMS41LDEuNSAwIDAsMSA0LDE5LjVBMS41LDEuNSAwIDAsMSAyLjUsMThBMS41LDEuNSAwIDAsMSA0LDE2LjVaIiAvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tree-view: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMiAxMVYzaC03djNIOVYzSDJ2OGg3VjhoMnYxMGg0djNoN3YtOGgtN3YzaC0yVjhoMnYzeiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMiAxNy4xODQ0IDIuOTY5NjggMTQuMzAzMiAxLjg2MDk0IDExLjQ0MDlaIi8+CiAgICA8cGF0aCBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiMzMzMzMzMiIHN0cm9rZT0iIzMzMzMzMyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOCA5Ljg2NzE5KSIgZD0iTTIuODYwMTUgNC44NjUzNUwwLjcyNjU0OSAyLjk5OTU5TDAgMy42MzA0NUwyLjg2MDE1IDYuMTMxNTdMOCAwLjYzMDg3Mkw3LjI3ODU3IDBMMi44NjAxNSA0Ljg2NTM1WiIvPgo8L3N2Zz4K);
  --jp-icon-undo: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjUgOGMtMi42NSAwLTUuMDUuOTktNi45IDIuNkwyIDd2OWg5bC0zLjYyLTMuNjJjMS4zOS0xLjE2IDMuMTYtMS44OCA1LjEyLTEuODggMy41NCAwIDYuNTUgMi4zMSA3LjYgNS41bDIuMzctLjc4QzIxLjA4IDExLjAzIDE3LjE1IDggMTIuNSA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-user: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE2IDdhNCA0IDAgMTEtOCAwIDQgNCAwIDAxOCAwek0xMiAxNGE3IDcgMCAwMC03IDdoMTRhNyA3IDAgMDAtNy03eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-users: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZlcnNpb249IjEuMSIgdmlld0JveD0iMCAwIDM2IDI0IiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgogPGcgY2xhc3M9ImpwLWljb24zIiB0cmFuc2Zvcm09Im1hdHJpeCgxLjczMjcgMCAwIDEuNzMyNyAtMy42MjgyIC4wOTk1NzcpIiBmaWxsPSIjNjE2MTYxIj4KICA8cGF0aCB0cmFuc2Zvcm09Im1hdHJpeCgxLjUsMCwwLDEuNSwwLC02KSIgZD0ibTEyLjE4NiA3LjUwOThjLTEuMDUzNSAwLTEuOTc1NyAwLjU2NjUtMi40Nzg1IDEuNDEwMiAwLjc1MDYxIDAuMzEyNzcgMS4zOTc0IDAuODI2NDggMS44NzMgMS40NzI3aDMuNDg2M2MwLTEuNTkyLTEuMjg4OS0yLjg4MjgtMi44ODA5LTIuODgyOHoiLz4KICA8cGF0aCBkPSJtMjAuNDY1IDIuMzg5NWEyLjE4ODUgMi4xODg1IDAgMCAxLTIuMTg4NCAyLjE4ODUgMi4xODg1IDIuMTg4NSAwIDAgMS0yLjE4ODUtMi4xODg1IDIuMTg4NSAyLjE4ODUgMCAwIDEgMi4xODg1LTIuMTg4NSAyLjE4ODUgMi4xODg1IDAgMCAxIDIuMTg4NCAyLjE4ODV6Ii8+CiAgPHBhdGggdHJhbnNmb3JtPSJtYXRyaXgoMS41LDAsMCwxLjUsMCwtNikiIGQ9Im0zLjU4OTggOC40MjE5Yy0xLjExMjYgMC0yLjAxMzcgMC45MDExMS0yLjAxMzcgMi4wMTM3aDIuODE0NWMwLjI2Nzk3LTAuMzczMDkgMC41OTA3LTAuNzA0MzUgMC45NTg5OC0wLjk3ODUyLTAuMzQ0MzMtMC42MTY4OC0xLjAwMzEtMS4wMzUyLTEuNzU5OC0xLjAzNTJ6Ii8+CiAgPHBhdGggZD0ibTYuOTE1NCA0LjYyM2ExLjUyOTQgMS41Mjk0IDAgMCAxLTEuNTI5NCAxLjUyOTQgMS41Mjk0IDEuNTI5NCAwIDAgMS0xLjUyOTQtMS41Mjk0IDEuNTI5NCAxLjUyOTQgMCAwIDEgMS41Mjk0LTEuNTI5NCAxLjUyOTQgMS41Mjk0IDAgMCAxIDEuNTI5NCAxLjUyOTR6Ii8+CiAgPHBhdGggZD0ibTYuMTM1IDEzLjUzNWMwLTMuMjM5MiAyLjYyNTktNS44NjUgNS44NjUtNS44NjUgMy4yMzkyIDAgNS44NjUgMi42MjU5IDUuODY1IDUuODY1eiIvPgogIDxjaXJjbGUgY3g9IjEyIiBjeT0iMy43Njg1IiByPSIyLjk2ODUiLz4KIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-vega: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbjEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjEyMTIxIj4KICAgIDxwYXRoIGQ9Ik0xMC42IDUuNGwyLjItMy4ySDIuMnY3LjNsNC02LjZ6Ii8+CiAgICA8cGF0aCBkPSJNMTUuOCAyLjJsLTQuNCA2LjZMNyA2LjNsLTQuOCA4djUuNWgxNy42VjIuMmgtNHptLTcgMTUuNEg1LjV2LTQuNGgzLjN2NC40em00LjQgMEg5LjhWOS44aDMuNHY3Ljh6bTQuNCAwaC0zLjRWNi41aDMuNHYxMS4xeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-word: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KIDxnIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzQxNDE0MSI+CiAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiA8L2c+CiA8ZyBjbGFzcz0ianAtaWNvbi1hY2NlbnQyIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSguNDMgLjA0MDEpIiBmaWxsPSIjZmZmIj4KICA8cGF0aCBkPSJtNC4xNCA4Ljc2cTAuMDY4Mi0xLjg5IDIuNDItMS44OSAxLjE2IDAgMS42OCAwLjQyIDAuNTY3IDAuNDEgMC41NjcgMS4xNnYzLjQ3cTAgMC40NjIgMC41MTQgMC40NjIgMC4xMDMgMCAwLjItMC4wMjMxdjAuNzE0cS0wLjM5OSAwLjEwMy0wLjY1MSAwLjEwMy0wLjQ1MiAwLTAuNjkzLTAuMjItMC4yMzEtMC4yLTAuMjg0LTAuNjYyLTAuOTU2IDAuODcyLTIgMC44NzItMC45MDMgMC0xLjQ3LTAuNDcyLTAuNTI1LTAuNDcyLTAuNTI1LTEuMjYgMC0wLjI2MiAwLjA0NTItMC40NzIgMC4wNTY3LTAuMjIgMC4xMTYtMC4zNzggMC4wNjgyLTAuMTY4IDAuMjMxLTAuMzA0IDAuMTU4LTAuMTQ3IDAuMjYyLTAuMjQyIDAuMTE2LTAuMDkxNCAwLjM2OC0wLjE2OCAwLjI2Mi0wLjA5MTQgMC4zOTktMC4xMjYgMC4xMzYtMC4wNDUyIDAuNDcyLTAuMTAzIDAuMzM2LTAuMDU3OCAwLjUwNC0wLjA3OTggMC4xNTgtMC4wMjMxIDAuNTY3LTAuMDc5OCAwLjU1Ni0wLjA2ODIgMC43NzctMC4yMjEgMC4yMi0wLjE1MiAwLjIyLTAuNDQxdi0wLjI1MnEwLTAuNDMtMC4zNTctMC42NjItMC4zMzYtMC4yMzEtMC45NzYtMC4yMzEtMC42NjIgMC0wLjk5OCAwLjI2Mi0wLjMzNiAwLjI1Mi0wLjM5OSAwLjc5OHptMS44OSAzLjY4cTAuNzg4IDAgMS4yNi0wLjQxIDAuNTA0LTAuNDIgMC41MDQtMC45MDN2LTEuMDVxLTAuMjg0IDAuMTM2LTAuODYxIDAuMjMxLTAuNTY3IDAuMDkxNC0wLjk4NyAwLjE1OC0wLjQyIDAuMDY4Mi0wLjc2NiAwLjMyNi0wLjMzNiAwLjI1Mi0wLjMzNiAwLjcwNHQwLjMwNCAwLjcwNCAwLjg2MSAwLjI1MnoiIHN0cm9rZS13aWR0aD0iMS4wNSIvPgogIDxwYXRoIGQ9Im0xMCA0LjU2aDAuOTQ1djMuMTVxMC42NTEtMC45NzYgMS44OS0wLjk3NiAxLjE2IDAgMS44OSAwLjg0IDAuNjgyIDAuODQgMC42ODIgMi4zMSAwIDEuNDctMC43MDQgMi40Mi0wLjcwNCAwLjg4Mi0xLjg5IDAuODgyLTEuMjYgMC0xLjg5LTEuMDJ2MC43NjZoLTAuODV6bTIuNjIgMy4wNHEtMC43NDYgMC0xLjE2IDAuNjQtMC40NTIgMC42My0wLjQ1MiAxLjY4IDAgMS4wNSAwLjQ1MiAxLjY4dDEuMTYgMC42M3EwLjc3NyAwIDEuMjYtMC42MyAwLjQ5NC0wLjY0IDAuNDk0LTEuNjggMC0xLjA1LTAuNDcyLTEuNjgtMC40NjItMC42NC0xLjI2LTAuNjR6IiBzdHJva2Utd2lkdGg9IjEuMDUiLz4KICA8cGF0aCBkPSJtMi43MyAxNS44IDEzLjYgMC4wMDgxYzAuMDA2OSAwIDAtMi42IDAtMi42IDAtMC4wMDc4LTEuMTUgMC0xLjE1IDAtMC4wMDY5IDAtMC4wMDgzIDEuNS0wLjAwODMgMS41LTJlLTMgLTAuMDAxNC0xMS4zLTAuMDAxNC0xMS4zLTAuMDAxNGwtMC4wMDU5Mi0xLjVjMC0wLjAwNzgtMS4xNyAwLjAwMTMtMS4xNyAwLjAwMTN6IiBzdHJva2Utd2lkdGg9Ii45NzUiLz4KIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-yaml: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1jb250cmFzdDIganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjRDgxQjYwIj4KICAgIDxwYXRoIGQ9Ik03LjIgMTguNnYtNS40TDMgNS42aDMuM2wxLjQgMy4xYy4zLjkuNiAxLjYgMSAyLjUuMy0uOC42LTEuNiAxLTIuNWwxLjQtMy4xaDMuNGwtNC40IDcuNnY1LjVsLTIuOS0uMXoiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxNi41IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxMSIgcj0iMi4xIi8+CiAgPC9nPgo8L3N2Zz4K);
}

/* Icon CSS class declarations */

.jp-AddAboveIcon {
  background-image: var(--jp-icon-add-above);
}

.jp-AddBelowIcon {
  background-image: var(--jp-icon-add-below);
}

.jp-AddIcon {
  background-image: var(--jp-icon-add);
}

.jp-BellIcon {
  background-image: var(--jp-icon-bell);
}

.jp-BugDotIcon {
  background-image: var(--jp-icon-bug-dot);
}

.jp-BugIcon {
  background-image: var(--jp-icon-bug);
}

.jp-BuildIcon {
  background-image: var(--jp-icon-build);
}

.jp-CaretDownEmptyIcon {
  background-image: var(--jp-icon-caret-down-empty);
}

.jp-CaretDownEmptyThinIcon {
  background-image: var(--jp-icon-caret-down-empty-thin);
}

.jp-CaretDownIcon {
  background-image: var(--jp-icon-caret-down);
}

.jp-CaretLeftIcon {
  background-image: var(--jp-icon-caret-left);
}

.jp-CaretRightIcon {
  background-image: var(--jp-icon-caret-right);
}

.jp-CaretUpEmptyThinIcon {
  background-image: var(--jp-icon-caret-up-empty-thin);
}

.jp-CaretUpIcon {
  background-image: var(--jp-icon-caret-up);
}

.jp-CaseSensitiveIcon {
  background-image: var(--jp-icon-case-sensitive);
}

.jp-CheckIcon {
  background-image: var(--jp-icon-check);
}

.jp-CircleEmptyIcon {
  background-image: var(--jp-icon-circle-empty);
}

.jp-CircleIcon {
  background-image: var(--jp-icon-circle);
}

.jp-ClearIcon {
  background-image: var(--jp-icon-clear);
}

.jp-CloseIcon {
  background-image: var(--jp-icon-close);
}

.jp-CodeCheckIcon {
  background-image: var(--jp-icon-code-check);
}

.jp-CodeIcon {
  background-image: var(--jp-icon-code);
}

.jp-CollapseAllIcon {
  background-image: var(--jp-icon-collapse-all);
}

.jp-ConsoleIcon {
  background-image: var(--jp-icon-console);
}

.jp-CopyIcon {
  background-image: var(--jp-icon-copy);
}

.jp-CopyrightIcon {
  background-image: var(--jp-icon-copyright);
}

.jp-CutIcon {
  background-image: var(--jp-icon-cut);
}

.jp-DeleteIcon {
  background-image: var(--jp-icon-delete);
}

.jp-DownloadIcon {
  background-image: var(--jp-icon-download);
}

.jp-DuplicateIcon {
  background-image: var(--jp-icon-duplicate);
}

.jp-EditIcon {
  background-image: var(--jp-icon-edit);
}

.jp-EllipsesIcon {
  background-image: var(--jp-icon-ellipses);
}

.jp-ErrorIcon {
  background-image: var(--jp-icon-error);
}

.jp-ExpandAllIcon {
  background-image: var(--jp-icon-expand-all);
}

.jp-ExtensionIcon {
  background-image: var(--jp-icon-extension);
}

.jp-FastForwardIcon {
  background-image: var(--jp-icon-fast-forward);
}

.jp-FileIcon {
  background-image: var(--jp-icon-file);
}

.jp-FileUploadIcon {
  background-image: var(--jp-icon-file-upload);
}

.jp-FilterDotIcon {
  background-image: var(--jp-icon-filter-dot);
}

.jp-FilterIcon {
  background-image: var(--jp-icon-filter);
}

.jp-FilterListIcon {
  background-image: var(--jp-icon-filter-list);
}

.jp-FolderFavoriteIcon {
  background-image: var(--jp-icon-folder-favorite);
}

.jp-FolderIcon {
  background-image: var(--jp-icon-folder);
}

.jp-HomeIcon {
  background-image: var(--jp-icon-home);
}

.jp-Html5Icon {
  background-image: var(--jp-icon-html5);
}

.jp-ImageIcon {
  background-image: var(--jp-icon-image);
}

.jp-InfoIcon {
  background-image: var(--jp-icon-info);
}

.jp-InspectorIcon {
  background-image: var(--jp-icon-inspector);
}

.jp-JsonIcon {
  background-image: var(--jp-icon-json);
}

.jp-JuliaIcon {
  background-image: var(--jp-icon-julia);
}

.jp-JupyterFaviconIcon {
  background-image: var(--jp-icon-jupyter-favicon);
}

.jp-JupyterIcon {
  background-image: var(--jp-icon-jupyter);
}

.jp-JupyterlabWordmarkIcon {
  background-image: var(--jp-icon-jupyterlab-wordmark);
}

.jp-KernelIcon {
  background-image: var(--jp-icon-kernel);
}

.jp-KeyboardIcon {
  background-image: var(--jp-icon-keyboard);
}

.jp-LaunchIcon {
  background-image: var(--jp-icon-launch);
}

.jp-LauncherIcon {
  background-image: var(--jp-icon-launcher);
}

.jp-LineFormIcon {
  background-image: var(--jp-icon-line-form);
}

.jp-LinkIcon {
  background-image: var(--jp-icon-link);
}

.jp-ListIcon {
  background-image: var(--jp-icon-list);
}

.jp-MarkdownIcon {
  background-image: var(--jp-icon-markdown);
}

.jp-MoveDownIcon {
  background-image: var(--jp-icon-move-down);
}

.jp-MoveUpIcon {
  background-image: var(--jp-icon-move-up);
}

.jp-NewFolderIcon {
  background-image: var(--jp-icon-new-folder);
}

.jp-NotTrustedIcon {
  background-image: var(--jp-icon-not-trusted);
}

.jp-NotebookIcon {
  background-image: var(--jp-icon-notebook);
}

.jp-NumberingIcon {
  background-image: var(--jp-icon-numbering);
}

.jp-OfflineBoltIcon {
  background-image: var(--jp-icon-offline-bolt);
}

.jp-PaletteIcon {
  background-image: var(--jp-icon-palette);
}

.jp-PasteIcon {
  background-image: var(--jp-icon-paste);
}

.jp-PdfIcon {
  background-image: var(--jp-icon-pdf);
}

.jp-PythonIcon {
  background-image: var(--jp-icon-python);
}

.jp-RKernelIcon {
  background-image: var(--jp-icon-r-kernel);
}

.jp-ReactIcon {
  background-image: var(--jp-icon-react);
}

.jp-RedoIcon {
  background-image: var(--jp-icon-redo);
}

.jp-RefreshIcon {
  background-image: var(--jp-icon-refresh);
}

.jp-RegexIcon {
  background-image: var(--jp-icon-regex);
}

.jp-RunIcon {
  background-image: var(--jp-icon-run);
}

.jp-RunningIcon {
  background-image: var(--jp-icon-running);
}

.jp-SaveIcon {
  background-image: var(--jp-icon-save);
}

.jp-SearchIcon {
  background-image: var(--jp-icon-search);
}

.jp-SettingsIcon {
  background-image: var(--jp-icon-settings);
}

.jp-ShareIcon {
  background-image: var(--jp-icon-share);
}

.jp-SpreadsheetIcon {
  background-image: var(--jp-icon-spreadsheet);
}

.jp-StopIcon {
  background-image: var(--jp-icon-stop);
}

.jp-TabIcon {
  background-image: var(--jp-icon-tab);
}

.jp-TableRowsIcon {
  background-image: var(--jp-icon-table-rows);
}

.jp-TagIcon {
  background-image: var(--jp-icon-tag);
}

.jp-TerminalIcon {
  background-image: var(--jp-icon-terminal);
}

.jp-TextEditorIcon {
  background-image: var(--jp-icon-text-editor);
}

.jp-TocIcon {
  background-image: var(--jp-icon-toc);
}

.jp-TreeViewIcon {
  background-image: var(--jp-icon-tree-view);
}

.jp-TrustedIcon {
  background-image: var(--jp-icon-trusted);
}

.jp-UndoIcon {
  background-image: var(--jp-icon-undo);
}

.jp-UserIcon {
  background-image: var(--jp-icon-user);
}

.jp-UsersIcon {
  background-image: var(--jp-icon-users);
}

.jp-VegaIcon {
  background-image: var(--jp-icon-vega);
}

.jp-WordIcon {
  background-image: var(--jp-icon-word);
}

.jp-YamlIcon {
  background-image: var(--jp-icon-yaml);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

.jp-Icon,
.jp-MaterialIcon {
  background-position: center;
  background-repeat: no-repeat;
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-cover {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/**
 * (DEPRECATED) Support for specific CSS icon sizes
 */

.jp-Icon-16 {
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-18 {
  background-size: 18px;
  min-width: 18px;
  min-height: 18px;
}

.jp-Icon-20 {
  background-size: 20px;
  min-width: 20px;
  min-height: 20px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.lm-TabBar .lm-TabBar-addButton {
  align-items: center;
  display: flex;
  padding: 4px;
  padding-bottom: 5px;
  margin-right: 1px;
  background-color: var(--jp-layout-color2);
}

.lm-TabBar .lm-TabBar-addButton:hover {
  background-color: var(--jp-layout-color1);
}

.lm-DockPanel-tabBar .lm-TabBar-tab {
  width: var(--jp-private-horizontal-tab-width);
}

.lm-DockPanel-tabBar .lm-TabBar-content {
  flex: unset;
}

.lm-DockPanel-tabBar[data-orientation='horizontal'] {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for icons as inline SVG HTMLElements
 */

/* recolor the primary elements of an icon */
.jp-icon0[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon1[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon2[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon3[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/* recolor the accent elements of an icon */
.jp-icon-accent0[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-accent1[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-accent2[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-accent3[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-accent4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-accent0[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-accent1[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-accent2[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-accent3[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-accent4[stroke] {
  stroke: var(--jp-layout-color4);
}

/* set the color of an icon to transparent */
.jp-icon-none[fill] {
  fill: none;
}

.jp-icon-none[stroke] {
  stroke: none;
}

/* brand icon colors. Same for light and dark */
.jp-icon-brand0[fill] {
  fill: var(--jp-brand-color0);
}

.jp-icon-brand1[fill] {
  fill: var(--jp-brand-color1);
}

.jp-icon-brand2[fill] {
  fill: var(--jp-brand-color2);
}

.jp-icon-brand3[fill] {
  fill: var(--jp-brand-color3);
}

.jp-icon-brand4[fill] {
  fill: var(--jp-brand-color4);
}

.jp-icon-brand0[stroke] {
  stroke: var(--jp-brand-color0);
}

.jp-icon-brand1[stroke] {
  stroke: var(--jp-brand-color1);
}

.jp-icon-brand2[stroke] {
  stroke: var(--jp-brand-color2);
}

.jp-icon-brand3[stroke] {
  stroke: var(--jp-brand-color3);
}

.jp-icon-brand4[stroke] {
  stroke: var(--jp-brand-color4);
}

/* warn icon colors. Same for light and dark */
.jp-icon-warn0[fill] {
  fill: var(--jp-warn-color0);
}

.jp-icon-warn1[fill] {
  fill: var(--jp-warn-color1);
}

.jp-icon-warn2[fill] {
  fill: var(--jp-warn-color2);
}

.jp-icon-warn3[fill] {
  fill: var(--jp-warn-color3);
}

.jp-icon-warn0[stroke] {
  stroke: var(--jp-warn-color0);
}

.jp-icon-warn1[stroke] {
  stroke: var(--jp-warn-color1);
}

.jp-icon-warn2[stroke] {
  stroke: var(--jp-warn-color2);
}

.jp-icon-warn3[stroke] {
  stroke: var(--jp-warn-color3);
}

/* icon colors that contrast well with each other and most backgrounds */
.jp-icon-contrast0[fill] {
  fill: var(--jp-icon-contrast-color0);
}

.jp-icon-contrast1[fill] {
  fill: var(--jp-icon-contrast-color1);
}

.jp-icon-contrast2[fill] {
  fill: var(--jp-icon-contrast-color2);
}

.jp-icon-contrast3[fill] {
  fill: var(--jp-icon-contrast-color3);
}

.jp-icon-contrast0[stroke] {
  stroke: var(--jp-icon-contrast-color0);
}

.jp-icon-contrast1[stroke] {
  stroke: var(--jp-icon-contrast-color1);
}

.jp-icon-contrast2[stroke] {
  stroke: var(--jp-icon-contrast-color2);
}

.jp-icon-contrast3[stroke] {
  stroke: var(--jp-icon-contrast-color3);
}

.jp-icon-dot[fill] {
  fill: var(--jp-warn-color0);
}

.jp-jupyter-icon-color[fill] {
  fill: var(--jp-jupyter-icon-color, var(--jp-warn-color0));
}

.jp-notebook-icon-color[fill] {
  fill: var(--jp-notebook-icon-color, var(--jp-warn-color0));
}

.jp-json-icon-color[fill] {
  fill: var(--jp-json-icon-color, var(--jp-warn-color1));
}

.jp-console-icon-color[fill] {
  fill: var(--jp-console-icon-color, white);
}

.jp-console-icon-background-color[fill] {
  fill: var(--jp-console-icon-background-color, var(--jp-brand-color1));
}

.jp-terminal-icon-color[fill] {
  fill: var(--jp-terminal-icon-color, var(--jp-layout-color2));
}

.jp-terminal-icon-background-color[fill] {
  fill: var(
    --jp-terminal-icon-background-color,
    var(--jp-inverse-layout-color2)
  );
}

.jp-text-editor-icon-color[fill] {
  fill: var(--jp-text-editor-icon-color, var(--jp-inverse-layout-color3));
}

.jp-inspector-icon-color[fill] {
  fill: var(--jp-inspector-icon-color, var(--jp-inverse-layout-color3));
}

/* CSS for icons in selected filebrowser listing items */
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}

.jp-DirListing-item.jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* stylelint-disable selector-max-class, selector-max-compound-selectors */

/**
* TODO: come up with non css-hack solution for showing the busy icon on top
*  of the close icon
* CSS for complex behavior of close icon of tabs in the main area tabbar
*/
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}

.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

/* stylelint-enable selector-max-class, selector-max-compound-selectors */

/* CSS for icons in status bar */
#jp-main-statusbar .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}

#jp-main-statusbar .jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* special handling for splash icon CSS. While the theme CSS reloads during
   splash, the splash icon can loose theming. To prevent that, we set a
   default for its color variable */
:root {
  --jp-warn-color0: var(--md-orange-700);
}

/* not sure what to do with this one, used in filebrowser listing */
.jp-DragIcon {
  margin-right: 4px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for alt colors for icons as inline SVG HTMLElements
 */

/* alt recolor the primary elements of an icon */
.jp-icon-alt .jp-icon0[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-alt .jp-icon1[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-alt .jp-icon2[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-alt .jp-icon3[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-alt .jp-icon4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-alt .jp-icon0[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-alt .jp-icon1[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-alt .jp-icon2[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-alt .jp-icon3[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-alt .jp-icon4[stroke] {
  stroke: var(--jp-layout-color4);
}

/* alt recolor the accent elements of an icon */
.jp-icon-alt .jp-icon-accent0[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon-alt .jp-icon-accent1[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon-alt .jp-icon-accent2[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon-alt .jp-icon-accent3[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon-alt .jp-icon-accent4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-alt .jp-icon-accent0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon-alt .jp-icon-accent1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon-alt .jp-icon-accent2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon-alt .jp-icon-accent3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon-alt .jp-icon-accent4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-icon-hoverShow:not(:hover) .jp-icon-hoverShow-content {
  display: none !important;
}

/**
 * Support for hover colors for icons as inline SVG HTMLElements
 */

/**
 * regular colors
 */

/* recolor the primary elements of an icon */
.jp-icon-hover :hover .jp-icon0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon-hover :hover .jp-icon1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon-hover :hover .jp-icon2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon-hover :hover .jp-icon3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon-hover :hover .jp-icon4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon-hover :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon-hover :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon-hover :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon-hover :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/* recolor the accent elements of an icon */
.jp-icon-hover :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-hover :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-hover :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-hover :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-hover :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-hover :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-hover :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-hover :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-hover :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* set the color of an icon to transparent */
.jp-icon-hover :hover .jp-icon-none-hover[fill] {
  fill: none;
}

.jp-icon-hover :hover .jp-icon-none-hover[stroke] {
  stroke: none;
}

/**
 * inverse colors
 */

/* inverse recolor the primary elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* inverse recolor the accent elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-IFrame {
  width: 100%;
  height: 100%;
}

.jp-IFrame > iframe {
  border: none;
}

/*
When drag events occur, `lm-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-IFrame {
  position: relative;
}

body.lm-mod-override-cursor .jp-IFrame::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-HoverBox {
  position: fixed;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-FormGroup-content fieldset {
  border: none;
  padding: 0;
  min-width: 0;
  width: 100%;
}

/* stylelint-disable selector-max-type */

.jp-FormGroup-content fieldset .jp-inputFieldWrapper input,
.jp-FormGroup-content fieldset .jp-inputFieldWrapper select,
.jp-FormGroup-content fieldset .jp-inputFieldWrapper textarea {
  font-size: var(--jp-content-font-size2);
  border-color: var(--jp-input-border-color);
  border-style: solid;
  border-radius: var(--jp-border-radius);
  border-width: 1px;
  padding: 6px 8px;
  background: none;
  color: var(--jp-ui-font-color0);
  height: inherit;
}

.jp-FormGroup-content fieldset input[type='checkbox'] {
  position: relative;
  top: 2px;
  margin-left: 0;
}

.jp-FormGroup-content button.jp-mod-styled {
  cursor: pointer;
}

.jp-FormGroup-content .checkbox label {
  cursor: pointer;
  font-size: var(--jp-content-font-size1);
}

.jp-FormGroup-content .jp-root > fieldset > legend {
  display: none;
}

.jp-FormGroup-content .jp-root > fieldset > p {
  display: none;
}

/** copy of `input.jp-mod-styled:focus` style */
.jp-FormGroup-content fieldset input:focus,
.jp-FormGroup-content fieldset select:focus {
  -moz-outline-radius: unset;
  outline: var(--jp-border-width) solid var(--md-blue-500);
  outline-offset: -1px;
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-FormGroup-content fieldset input:hover:not(:focus),
.jp-FormGroup-content fieldset select:hover:not(:focus) {
  background-color: var(--jp-border-color2);
}

/* stylelint-enable selector-max-type */

.jp-FormGroup-content .checkbox .field-description {
  /* Disable default description field for checkbox:
   because other widgets do not have description fields,
   we add descriptions to each widget on the field level.
  */
  display: none;
}

.jp-FormGroup-content #root__description {
  display: none;
}

.jp-FormGroup-content .jp-modifiedIndicator {
  width: 5px;
  background-color: var(--jp-brand-color2);
  margin-top: 0;
  margin-left: calc(var(--jp-private-settingeditor-modifier-indent) * -1);
  flex-shrink: 0;
}

.jp-FormGroup-content .jp-modifiedIndicator.jp-errorIndicator {
  background-color: var(--jp-error-color0);
  margin-right: 0.5em;
}

/* RJSF ARRAY style */

.jp-arrayFieldWrapper legend {
  font-size: var(--jp-content-font-size2);
  color: var(--jp-ui-font-color0);
  flex-basis: 100%;
  padding: 4px 0;
  font-weight: var(--jp-content-heading-font-weight);
  border-bottom: 1px solid var(--jp-border-color2);
}

.jp-arrayFieldWrapper .field-description {
  padding: 4px 0;
  white-space: pre-wrap;
}

.jp-arrayFieldWrapper .array-item {
  width: 100%;
  border: 1px solid var(--jp-border-color2);
  border-radius: 4px;
  margin: 4px;
}

.jp-ArrayOperations {
  display: flex;
  margin-left: 8px;
}

.jp-ArrayOperationsButton {
  margin: 2px;
}

.jp-ArrayOperationsButton .jp-icon3[fill] {
  fill: var(--jp-ui-font-color0);
}

button.jp-ArrayOperationsButton.jp-mod-styled:disabled {
  cursor: not-allowed;
  opacity: 0.5;
}

/* RJSF form validation error */

.jp-FormGroup-content .validationErrors {
  color: var(--jp-error-color0);
}

/* Hide panel level error as duplicated the field level error */
.jp-FormGroup-content .panel.errors {
  display: none;
}

/* RJSF normal content (settings-editor) */

.jp-FormGroup-contentNormal {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

.jp-FormGroup-contentNormal .jp-FormGroup-contentItem {
  margin-left: 7px;
  color: var(--jp-ui-font-color0);
}

.jp-FormGroup-contentNormal .jp-FormGroup-description {
  flex-basis: 100%;
  padding: 4px 7px;
}

.jp-FormGroup-contentNormal .jp-FormGroup-default {
  flex-basis: 100%;
  padding: 4px 7px;
}

.jp-FormGroup-contentNormal .jp-FormGroup-fieldLabel {
  font-size: var(--jp-content-font-size1);
  font-weight: normal;
  min-width: 120px;
}

.jp-FormGroup-contentNormal fieldset:not(:first-child) {
  margin-left: 7px;
}

.jp-FormGroup-contentNormal .field-array-of-string .array-item {
  /* Display `jp-ArrayOperations` buttons side-by-side with content except
    for small screens where flex-wrap will place them one below the other.
  */
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

.jp-FormGroup-contentNormal .jp-objectFieldWrapper .form-group {
  padding: 2px 8px 2px var(--jp-private-settingeditor-modifier-indent);
  margin-top: 2px;
}

/* RJSF compact content (metadata-form) */

.jp-FormGroup-content.jp-FormGroup-contentCompact {
  width: 100%;
}

.jp-FormGroup-contentCompact .form-group {
  display: flex;
  padding: 0.5em 0.2em 0.5em 0;
}

.jp-FormGroup-contentCompact
  .jp-FormGroup-compactTitle
  .jp-FormGroup-description {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color2);
}

.jp-FormGroup-contentCompact .jp-FormGroup-fieldLabel {
  padding-bottom: 0.3em;
}

.jp-FormGroup-contentCompact .jp-inputFieldWrapper .form-control {
  width: 100%;
  box-sizing: border-box;
}

.jp-FormGroup-contentCompact .jp-arrayFieldWrapper .jp-FormGroup-compactTitle {
  padding-bottom: 7px;
}

.jp-FormGroup-contentCompact
  .jp-objectFieldWrapper
  .jp-objectFieldWrapper
  .form-group {
  padding: 2px 8px 2px var(--jp-private-settingeditor-modifier-indent);
  margin-top: 2px;
}

.jp-FormGroup-contentCompact ul.error-detail {
  margin-block-start: 0.5em;
  margin-block-end: 0.5em;
  padding-inline-start: 1em;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-SidePanel {
  display: flex;
  flex-direction: column;
  min-width: var(--jp-sidebar-min-width);
  overflow-y: auto;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  font-size: var(--jp-ui-font-size1);
}

.jp-SidePanel-header {
  flex: 0 0 auto;
  display: flex;
  border-bottom: var(--jp-border-width) solid var(--jp-border-color2);
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  letter-spacing: 1px;
  margin: 0;
  padding: 2px;
  text-transform: uppercase;
}

.jp-SidePanel-toolbar {
  flex: 0 0 auto;
}

.jp-SidePanel-content {
  flex: 1 1 auto;
}

.jp-SidePanel-toolbar,
.jp-AccordionPanel-toolbar {
  height: var(--jp-private-toolbar-height);
}

.jp-SidePanel-toolbar.jp-Toolbar-micro {
  display: none;
}

.lm-AccordionPanel .jp-AccordionPanel-title {
  box-sizing: border-box;
  line-height: 25px;
  margin: 0;
  display: flex;
  align-items: center;
  background: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  font-size: var(--jp-ui-font-size0);
}

.jp-AccordionPanel-title {
  cursor: pointer;
  user-select: none;
  -moz-user-select: none;
  -webkit-user-select: none;
  text-transform: uppercase;
}

.lm-AccordionPanel[data-orientation='horizontal'] > .jp-AccordionPanel-title {
  /* Title is rotated for horizontal accordion panel using CSS */
  display: block;
  transform-origin: top left;
  transform: rotate(-90deg) translate(-100%);
}

.jp-AccordionPanel-title .lm-AccordionPanel-titleLabel {
  user-select: none;
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
}

.jp-AccordionPanel-title .lm-AccordionPanel-titleCollapser {
  transform: rotate(-90deg);
  margin: auto 0;
  height: 16px;
}

.jp-AccordionPanel-title.lm-mod-expanded .lm-AccordionPanel-titleCollapser {
  transform: rotate(0deg);
}

.lm-AccordionPanel .jp-AccordionPanel-toolbar {
  background: none;
  box-shadow: none;
  border: none;
  margin-left: auto;
}

.lm-AccordionPanel .lm-SplitPanel-handle:hover {
  background: var(--jp-layout-color3);
}

.jp-text-truncated {
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Spinner {
  position: absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 10;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-layout-color0);
  outline: none;
}

.jp-SpinnerContent {
  font-size: 10px;
  margin: 50px auto;
  text-indent: -9999em;
  width: 3em;
  height: 3em;
  border-radius: 50%;
  background: var(--jp-brand-color3);
  background: linear-gradient(
    to right,
    #f37626 10%,
    rgba(255, 255, 255, 0) 42%
  );
  position: relative;
  animation: load3 1s infinite linear, fadeIn 1s;
}

.jp-SpinnerContent::before {
  width: 50%;
  height: 50%;
  background: #f37626;
  border-radius: 100% 0 0;
  position: absolute;
  top: 0;
  left: 0;
  content: '';
}

.jp-SpinnerContent::after {
  background: var(--jp-layout-color0);
  width: 75%;
  height: 75%;
  border-radius: 50%;
  content: '';
  margin: auto;
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
}

@keyframes fadeIn {
  0% {
    opacity: 0;
  }

  100% {
    opacity: 1;
  }
}

@keyframes load3 {
  0% {
    transform: rotate(0deg);
  }

  100% {
    transform: rotate(360deg);
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

button.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: none;
  box-sizing: border-box;
  text-align: center;
  line-height: 32px;
  height: 32px;
  padding: 0 12px;
  letter-spacing: 0.8px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input.jp-mod-styled {
  background: var(--jp-input-background);
  height: 28px;
  box-sizing: border-box;
  border: var(--jp-border-width) solid var(--jp-border-color1);
  padding-left: 7px;
  padding-right: 7px;
  font-size: var(--jp-ui-font-size2);
  color: var(--jp-ui-font-color0);
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input[type='checkbox'].jp-mod-styled {
  appearance: checkbox;
  -webkit-appearance: checkbox;
  -moz-appearance: checkbox;
  height: auto;
}

input.jp-mod-styled:focus {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-select-wrapper {
  display: flex;
  position: relative;
  flex-direction: column;
  padding: 1px;
  background-color: var(--jp-layout-color1);
  box-sizing: border-box;
  margin-bottom: 12px;
}

.jp-select-wrapper:not(.multiple) {
  height: 28px;
}

.jp-select-wrapper.jp-mod-focused select.jp-mod-styled {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-input-active-background);
}

select.jp-mod-styled:hover {
  cursor: pointer;
  color: var(--jp-ui-font-color0);
  background-color: var(--jp-input-hover-background);
  box-shadow: inset 0 0 1px rgba(0, 0, 0, 0.5);
}

select.jp-mod-styled {
  flex: 1 1 auto;
  width: 100%;
  font-size: var(--jp-ui-font-size2);
  background: var(--jp-input-background);
  color: var(--jp-ui-font-color0);
  padding: 0 25px 0 8px;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

select.jp-mod-styled:not([multiple]) {
  height: 32px;
}

select.jp-mod-styled[multiple] {
  max-height: 200px;
  overflow-y: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-switch {
  display: flex;
  align-items: center;
  padding-left: 4px;
  padding-right: 4px;
  font-size: var(--jp-ui-font-size1);
  background-color: transparent;
  color: var(--jp-ui-font-color1);
  border: none;
  height: 20px;
}

.jp-switch:hover {
  background-color: var(--jp-layout-color2);
}

.jp-switch-label {
  margin-right: 5px;
  font-family: var(--jp-ui-font-family);
}

.jp-switch-track {
  cursor: pointer;
  background-color: var(--jp-switch-color, var(--jp-border-color1));
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 34px;
  height: 16px;
  width: 35px;
  position: relative;
}

.jp-switch-track::before {
  content: '';
  position: absolute;
  height: 10px;
  width: 10px;
  margin: 3px;
  left: 0;
  background-color: var(--jp-ui-inverse-font-color1);
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 50%;
}

.jp-switch[aria-checked='true'] .jp-switch-track {
  background-color: var(--jp-switch-true-position-color, var(--jp-warn-color0));
}

.jp-switch[aria-checked='true'] .jp-switch-track::before {
  /* track width (35) - margins (3 + 3) - thumb width (10) */
  left: 19px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

:root {
  --jp-private-toolbar-height: calc(
    28px + var(--jp-border-width)
  ); /* leave 28px for content */
}

.jp-Toolbar {
  color: var(--jp-ui-font-color1);
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  background: var(--jp-toolbar-background);
  min-height: var(--jp-toolbar-micro-height);
  padding: 2px;
  z-index: 8;
  overflow-x: hidden;
}

/* Toolbar items */

.jp-Toolbar > .jp-Toolbar-item.jp-Toolbar-spacer {
  flex-grow: 1;
  flex-shrink: 1;
}

.jp-Toolbar-item.jp-Toolbar-kernelStatus {
  display: inline-block;
  width: 32px;
  background-repeat: no-repeat;
  background-position: center;
  background-size: 16px;
}

.jp-Toolbar > .jp-Toolbar-item {
  flex: 0 0 auto;
  display: flex;
  padding-left: 1px;
  padding-right: 1px;
  font-size: var(--jp-ui-font-size1);
  line-height: var(--jp-private-toolbar-height);
  height: 100%;
}

/* Toolbar buttons */

/* This is the div we use to wrap the react component into a Widget */
div.jp-ToolbarButton {
  color: transparent;
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0;
  margin: 0;
}

button.jp-ToolbarButtonComponent {
  background: var(--jp-layout-color1);
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0 6px;
  margin: 0;
  height: 24px;
  border-radius: var(--jp-border-radius);
  display: flex;
  align-items: center;
  text-align: center;
  font-size: 14px;
  min-width: unset;
  min-height: unset;
}

button.jp-ToolbarButtonComponent:disabled {
  opacity: 0.4;
}

button.jp-ToolbarButtonComponent > span {
  padding: 0;
  flex: 0 0 auto;
}

button.jp-ToolbarButtonComponent .jp-ToolbarButtonComponent-label {
  font-size: var(--jp-ui-font-size1);
  line-height: 100%;
  padding-left: 2px;
  color: var(--jp-ui-font-color1);
  font-family: var(--jp-ui-font-family);
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar.jp-Toolbar-micro {
  padding: 0;
  min-height: 0;
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar {
  border: none;
  box-shadow: none;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-WindowedPanel-outer {
  position: relative;
  overflow-y: auto;
}

.jp-WindowedPanel-inner {
  position: relative;
}

.jp-WindowedPanel-window {
  position: absolute;
  left: 0;
  right: 0;
  overflow: visible;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* Sibling imports */

body {
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
}

/* Disable native link decoration styles everywhere outside of dialog boxes */
a {
  text-decoration: unset;
  color: unset;
}

a:hover {
  text-decoration: unset;
  color: unset;
}

/* Accessibility for links inside dialog box text */
.jp-Dialog-content a {
  text-decoration: revert;
  color: var(--jp-content-link-color);
}

.jp-Dialog-content a:hover {
  text-decoration: revert;
}

/* Styles for ui-components */
.jp-Button {
  color: var(--jp-ui-font-color2);
  border-radius: var(--jp-border-radius);
  padding: 0 12px;
  font-size: var(--jp-ui-font-size1);

  /* Copy from blueprint 3 */
  display: inline-flex;
  flex-direction: row;
  border: none;
  cursor: pointer;
  align-items: center;
  justify-content: center;
  text-align: left;
  vertical-align: middle;
  min-height: 30px;
  min-width: 30px;
}

.jp-Button:disabled {
  cursor: not-allowed;
}

.jp-Button:empty {
  padding: 0 !important;
}

.jp-Button.jp-mod-small {
  min-height: 24px;
  min-width: 24px;
  font-size: 12px;
  padding: 0 7px;
}

/* Use our own theme for hover styles */
.jp-Button.jp-mod-minimal:hover {
  background-color: var(--jp-layout-color2);
}

.jp-Button.jp-mod-minimal {
  background: none;
}

.jp-InputGroup {
  display: block;
  position: relative;
}

.jp-InputGroup input {
  box-sizing: border-box;
  border: none;
  border-radius: 0;
  background-color: transparent;
  color: var(--jp-ui-font-color0);
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
  padding-bottom: 0;
  padding-top: 0;
  padding-left: 10px;
  padding-right: 28px;
  position: relative;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  font-size: 14px;
  font-weight: 400;
  height: 30px;
  line-height: 30px;
  outline: none;
  vertical-align: middle;
}

.jp-InputGroup input:focus {
  box-shadow: inset 0 0 0 var(--jp-border-width)
      var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-InputGroup input:disabled {
  cursor: not-allowed;
  resize: block;
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color2);
}

.jp-InputGroup input:disabled ~ span {
  cursor: not-allowed;
  color: var(--jp-ui-font-color2);
}

.jp-InputGroup input::placeholder,
input::placeholder {
  color: var(--jp-ui-font-color2);
}

.jp-InputGroupAction {
  position: absolute;
  bottom: 1px;
  right: 0;
  padding: 6px;
}

.jp-HTMLSelect.jp-DefaultStyle select {
  background-color: initial;
  border: none;
  border-radius: 0;
  box-shadow: none;
  color: var(--jp-ui-font-color0);
  display: block;
  font-size: var(--jp-ui-font-size1);
  font-family: var(--jp-ui-font-family);
  height: 24px;
  line-height: 14px;
  padding: 0 25px 0 10px;
  text-align: left;
  -moz-appearance: none;
  -webkit-appearance: none;
}

.jp-HTMLSelect.jp-DefaultStyle select:disabled {
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color2);
  cursor: not-allowed;
  resize: block;
}

.jp-HTMLSelect.jp-DefaultStyle select:disabled ~ span {
  cursor: not-allowed;
}

/* Use our own theme for hover and option styles */
/* stylelint-disable-next-line selector-max-type */
.jp-HTMLSelect.jp-DefaultStyle select:hover,
.jp-HTMLSelect.jp-DefaultStyle select > option {
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color0);
}

select {
  box-sizing: border-box;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-StatusBar-Widget {
  display: flex;
  align-items: center;
  background: var(--jp-layout-color2);
  min-height: var(--jp-statusbar-height);
  justify-content: space-between;
  padding: 0 10px;
}

.jp-StatusBar-Left {
  display: flex;
  align-items: center;
  flex-direction: row;
}

.jp-StatusBar-Middle {
  display: flex;
  align-items: center;
}

.jp-StatusBar-Right {
  display: flex;
  align-items: center;
  flex-direction: row-reverse;
}

.jp-StatusBar-Item {
  max-height: var(--jp-statusbar-height);
  margin: 0 2px;
  height: var(--jp-statusbar-height);
  white-space: nowrap;
  text-overflow: ellipsis;
  color: var(--jp-ui-font-color1);
  padding: 0 6px;
}

.jp-mod-highlighted:hover {
  background-color: var(--jp-layout-color3);
}

.jp-mod-clicked {
  background-color: var(--jp-brand-color1);
}

.jp-mod-clicked:hover {
  background-color: var(--jp-brand-color0);
}

.jp-mod-clicked .jp-StatusBar-TextItem {
  color: var(--jp-ui-inverse-font-color1);
}

.jp-StatusBar-HoverItem {
  box-shadow: '0px 4px 4px rgba(0, 0, 0, 0.25)';
}

.jp-StatusBar-TextItem {
  font-size: var(--jp-ui-font-size1);
  font-family: var(--jp-ui-font-family);
  line-height: 24px;
  color: var(--jp-ui-font-color1);
}

.jp-StatusBar-GroupItem {
  display: flex;
  align-items: center;
  flex-direction: row;
}

.jp-Statusbar-ProgressCircle svg {
  display: block;
  margin: 0 auto;
  width: 16px;
  height: 24px;
  align-self: normal;
}

.jp-Statusbar-ProgressCircle path {
  fill: var(--jp-inverse-layout-color3);
}

.jp-Statusbar-ProgressBar-progress-bar {
  height: 10px;
  width: 100px;
  border: solid 0.25px var(--jp-brand-color2);
  border-radius: 3px;
  overflow: hidden;
  align-self: center;
}

.jp-Statusbar-ProgressBar-progress-bar > div {
  background-color: var(--jp-brand-color2);
  background-image: linear-gradient(
    -45deg,
    rgba(255, 255, 255, 0.2) 25%,
    transparent 25%,
    transparent 50%,
    rgba(255, 255, 255, 0.2) 50%,
    rgba(255, 255, 255, 0.2) 75%,
    transparent 75%,
    transparent
  );
  background-size: 40px 40px;
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 14px;
  color: #fff;
  text-align: center;
  animation: jp-Statusbar-ExecutionTime-progress-bar 2s linear infinite;
}

.jp-Statusbar-ProgressBar-progress-bar p {
  color: var(--jp-ui-font-color1);
  font-family: var(--jp-ui-font-family);
  font-size: var(--jp-ui-font-size1);
  line-height: 10px;
  width: 100px;
}

@keyframes jp-Statusbar-ExecutionTime-progress-bar {
  0% {
    background-position: 0 0;
  }

  100% {
    background-position: 40px 40px;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-commandpalette-search-height: 28px;
}

/*-----------------------------------------------------------------------------
| Overall styles
|----------------------------------------------------------------------------*/

.lm-CommandPalette {
  padding-bottom: 0;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);

  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Modal variant
|----------------------------------------------------------------------------*/

.jp-ModalCommandPalette {
  position: absolute;
  z-index: 10000;
  top: 38px;
  left: 30%;
  margin: 0;
  padding: 4px;
  width: 40%;
  box-shadow: var(--jp-elevation-z4);
  border-radius: 4px;
  background: var(--jp-layout-color0);
}

.jp-ModalCommandPalette .lm-CommandPalette {
  max-height: 40vh;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-close-icon::after {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-header {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-item {
  margin-left: 4px;
  margin-right: 4px;
}

.jp-ModalCommandPalette
  .lm-CommandPalette
  .lm-CommandPalette-item.lm-mod-disabled {
  display: none;
}

/*-----------------------------------------------------------------------------
| Search
|----------------------------------------------------------------------------*/

.lm-CommandPalette-search {
  padding: 4px;
  background-color: var(--jp-layout-color1);
  z-index: 2;
}

.lm-CommandPalette-wrapper {
  overflow: overlay;
  padding: 0 9px;
  background-color: var(--jp-input-active-background);
  height: 30px;
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.lm-CommandPalette.lm-mod-focused .lm-CommandPalette-wrapper {
  box-shadow: inset 0 0 0 1px var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-SearchIconGroup {
  color: white;
  background-color: var(--jp-brand-color1);
  position: absolute;
  top: 4px;
  right: 4px;
  padding: 5px 5px 1px;
}

.jp-SearchIconGroup svg {
  height: 20px;
  width: 20px;
}

.jp-SearchIconGroup .jp-icon3[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-input {
  background: transparent;
  width: calc(100% - 18px);
  float: left;
  border: none;
  outline: none;
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  line-height: var(--jp-private-commandpalette-search-height);
}

.lm-CommandPalette-input::-webkit-input-placeholder,
.lm-CommandPalette-input::-moz-placeholder,
.lm-CommandPalette-input:-ms-input-placeholder {
  color: var(--jp-ui-font-color2);
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Results
|----------------------------------------------------------------------------*/

.lm-CommandPalette-header:first-child {
  margin-top: 0;
}

.lm-CommandPalette-header {
  border-bottom: solid var(--jp-border-width) var(--jp-border-color2);
  color: var(--jp-ui-font-color1);
  cursor: pointer;
  display: flex;
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  letter-spacing: 1px;
  margin-top: 8px;
  padding: 8px 0 8px 12px;
  text-transform: uppercase;
}

.lm-CommandPalette-header.lm-mod-active {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-header > mark {
  background-color: transparent;
  font-weight: bold;
  color: var(--jp-ui-font-color1);
}

.lm-CommandPalette-item {
  padding: 4px 12px 4px 4px;
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  font-weight: 400;
  display: flex;
}

.lm-CommandPalette-item.lm-mod-disabled {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item.lm-mod-active {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item.lm-mod-active .lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-inverse-font-color0);
}

.lm-CommandPalette-item.lm-mod-active .jp-icon-selectable[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-item.lm-mod-active:hover:not(.lm-mod-disabled) {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item:hover:not(.lm-mod-active):not(.lm-mod-disabled) {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-itemContent {
  overflow: hidden;
}

.lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.lm-CommandPalette-item.lm-mod-disabled mark {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item .lm-CommandPalette-itemIcon {
  margin: 0 4px 0 0;
  position: relative;
  width: 16px;
  top: 2px;
  flex: 0 0 auto;
}

.lm-CommandPalette-item.lm-mod-disabled .lm-CommandPalette-itemIcon {
  opacity: 0.6;
}

.lm-CommandPalette-item .lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemCaption {
  display: none;
}

.lm-CommandPalette-content {
  background-color: var(--jp-layout-color1);
}

.lm-CommandPalette-content:empty::after {
  content: 'No results';
  margin: auto;
  margin-top: 20px;
  width: 100px;
  display: block;
  font-size: var(--jp-ui-font-size2);
  font-family: var(--jp-ui-font-family);
  font-weight: lighter;
}

.lm-CommandPalette-emptyMessage {
  text-align: center;
  margin-top: 24px;
  line-height: 1.32;
  padding: 0 8px;
  color: var(--jp-content-font-color3);
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Dialog {
  position: absolute;
  z-index: 10000;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  top: 0;
  left: 0;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-dialog-background);
}

.jp-Dialog-content {
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
  background: var(--jp-layout-color1);
  padding: 24px 24px 12px;
  min-width: 300px;
  min-height: 150px;
  max-width: 1000px;
  max-height: 500px;
  box-sizing: border-box;
  box-shadow: var(--jp-elevation-z20);
  word-wrap: break-word;
  border-radius: var(--jp-border-radius);

  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color1);
  resize: both;
}

.jp-Dialog-content.jp-Dialog-content-small {
  max-width: 500px;
}

.jp-Dialog-button {
  overflow: visible;
}

button.jp-Dialog-button:focus {
  outline: 1px solid var(--jp-brand-color1);
  outline-offset: 4px;
  -moz-outline-radius: 0;
}

button.jp-Dialog-button:focus::-moz-focus-inner {
  border: 0;
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-accept:focus,
button.jp-Dialog-button.jp-mod-styled.jp-mod-warn:focus,
button.jp-Dialog-button.jp-mod-styled.jp-mod-reject:focus {
  outline-offset: 4px;
  -moz-outline-radius: 0;
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-accept:focus {
  outline: 1px solid var(--jp-accept-color-normal, var(--jp-brand-color1));
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-warn:focus {
  outline: 1px solid var(--jp-warn-color-normal, var(--jp-error-color1));
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-reject:focus {
  outline: 1px solid var(--jp-reject-color-normal, var(--md-grey-600));
}

button.jp-Dialog-close-button {
  padding: 0;
  height: 100%;
  min-width: unset;
  min-height: unset;
}

.jp-Dialog-header {
  display: flex;
  justify-content: space-between;
  flex: 0 0 auto;
  padding-bottom: 12px;
  font-size: var(--jp-ui-font-size3);
  font-weight: 400;
  color: var(--jp-ui-font-color1);
}

.jp-Dialog-body {
  display: flex;
  flex-direction: column;
  flex: 1 1 auto;
  font-size: var(--jp-ui-font-size1);
  background: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  overflow: auto;
}

.jp-Dialog-footer {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  align-items: center;
  flex: 0 0 auto;
  margin-left: -12px;
  margin-right: -12px;
  padding: 12px;
}

.jp-Dialog-checkbox {
  padding-right: 5px;
}

.jp-Dialog-checkbox > input:focus-visible {
  outline: 1px solid var(--jp-input-active-border-color);
  outline-offset: 1px;
}

.jp-Dialog-spacer {
  flex: 1 1 auto;
}

.jp-Dialog-title {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.jp-Dialog-body > .jp-select-wrapper {
  width: 100%;
}

.jp-Dialog-body > button {
  padding: 0 16px;
}

.jp-Dialog-body > label {
  line-height: 1.4;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-button.jp-mod-styled:not(:last-child) {
  margin-right: 12px;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-Input-Boolean-Dialog {
  flex-direction: row-reverse;
  align-items: end;
  width: 100%;
}

.jp-Input-Boolean-Dialog > label {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MainAreaWidget > :focus {
  outline: none;
}

.jp-MainAreaWidget .jp-MainAreaWidget-error {
  padding: 6px;
}

.jp-MainAreaWidget .jp-MainAreaWidget-error > pre {
  width: auto;
  padding: 10px;
  background: var(--jp-error-color3);
  border: var(--jp-border-width) solid var(--jp-error-color1);
  border-radius: var(--jp-border-radius);
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  white-space: pre-wrap;
  word-wrap: break-word;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/**
 * google-material-color v1.2.6
 * https://github.com/danlevan/google-material-color
 */
:root {
  --md-red-50: #ffebee;
  --md-red-100: #ffcdd2;
  --md-red-200: #ef9a9a;
  --md-red-300: #e57373;
  --md-red-400: #ef5350;
  --md-red-500: #f44336;
  --md-red-600: #e53935;
  --md-red-700: #d32f2f;
  --md-red-800: #c62828;
  --md-red-900: #b71c1c;
  --md-red-A100: #ff8a80;
  --md-red-A200: #ff5252;
  --md-red-A400: #ff1744;
  --md-red-A700: #d50000;
  --md-pink-50: #fce4ec;
  --md-pink-100: #f8bbd0;
  --md-pink-200: #f48fb1;
  --md-pink-300: #f06292;
  --md-pink-400: #ec407a;
  --md-pink-500: #e91e63;
  --md-pink-600: #d81b60;
  --md-pink-700: #c2185b;
  --md-pink-800: #ad1457;
  --md-pink-900: #880e4f;
  --md-pink-A100: #ff80ab;
  --md-pink-A200: #ff4081;
  --md-pink-A400: #f50057;
  --md-pink-A700: #c51162;
  --md-purple-50: #f3e5f5;
  --md-purple-100: #e1bee7;
  --md-purple-200: #ce93d8;
  --md-purple-300: #ba68c8;
  --md-purple-400: #ab47bc;
  --md-purple-500: #9c27b0;
  --md-purple-600: #8e24aa;
  --md-purple-700: #7b1fa2;
  --md-purple-800: #6a1b9a;
  --md-purple-900: #4a148c;
  --md-purple-A100: #ea80fc;
  --md-purple-A200: #e040fb;
  --md-purple-A400: #d500f9;
  --md-purple-A700: #a0f;
  --md-deep-purple-50: #ede7f6;
  --md-deep-purple-100: #d1c4e9;
  --md-deep-purple-200: #b39ddb;
  --md-deep-purple-300: #9575cd;
  --md-deep-purple-400: #7e57c2;
  --md-deep-purple-500: #673ab7;
  --md-deep-purple-600: #5e35b1;
  --md-deep-purple-700: #512da8;
  --md-deep-purple-800: #4527a0;
  --md-deep-purple-900: #311b92;
  --md-deep-purple-A100: #b388ff;
  --md-deep-purple-A200: #7c4dff;
  --md-deep-purple-A400: #651fff;
  --md-deep-purple-A700: #6200ea;
  --md-indigo-50: #e8eaf6;
  --md-indigo-100: #c5cae9;
  --md-indigo-200: #9fa8da;
  --md-indigo-300: #7986cb;
  --md-indigo-400: #5c6bc0;
  --md-indigo-500: #3f51b5;
  --md-indigo-600: #3949ab;
  --md-indigo-700: #303f9f;
  --md-indigo-800: #283593;
  --md-indigo-900: #1a237e;
  --md-indigo-A100: #8c9eff;
  --md-indigo-A200: #536dfe;
  --md-indigo-A400: #3d5afe;
  --md-indigo-A700: #304ffe;
  --md-blue-50: #e3f2fd;
  --md-blue-100: #bbdefb;
  --md-blue-200: #90caf9;
  --md-blue-300: #64b5f6;
  --md-blue-400: #42a5f5;
  --md-blue-500: #2196f3;
  --md-blue-600: #1e88e5;
  --md-blue-700: #1976d2;
  --md-blue-800: #1565c0;
  --md-blue-900: #0d47a1;
  --md-blue-A100: #82b1ff;
  --md-blue-A200: #448aff;
  --md-blue-A400: #2979ff;
  --md-blue-A700: #2962ff;
  --md-light-blue-50: #e1f5fe;
  --md-light-blue-100: #b3e5fc;
  --md-light-blue-200: #81d4fa;
  --md-light-blue-300: #4fc3f7;
  --md-light-blue-400: #29b6f6;
  --md-light-blue-500: #03a9f4;
  --md-light-blue-600: #039be5;
  --md-light-blue-700: #0288d1;
  --md-light-blue-800: #0277bd;
  --md-light-blue-900: #01579b;
  --md-light-blue-A100: #80d8ff;
  --md-light-blue-A200: #40c4ff;
  --md-light-blue-A400: #00b0ff;
  --md-light-blue-A700: #0091ea;
  --md-cyan-50: #e0f7fa;
  --md-cyan-100: #b2ebf2;
  --md-cyan-200: #80deea;
  --md-cyan-300: #4dd0e1;
  --md-cyan-400: #26c6da;
  --md-cyan-500: #00bcd4;
  --md-cyan-600: #00acc1;
  --md-cyan-700: #0097a7;
  --md-cyan-800: #00838f;
  --md-cyan-900: #006064;
  --md-cyan-A100: #84ffff;
  --md-cyan-A200: #18ffff;
  --md-cyan-A400: #00e5ff;
  --md-cyan-A700: #00b8d4;
  --md-teal-50: #e0f2f1;
  --md-teal-100: #b2dfdb;
  --md-teal-200: #80cbc4;
  --md-teal-300: #4db6ac;
  --md-teal-400: #26a69a;
  --md-teal-500: #009688;
  --md-teal-600: #00897b;
  --md-teal-700: #00796b;
  --md-teal-800: #00695c;
  --md-teal-900: #004d40;
  --md-teal-A100: #a7ffeb;
  --md-teal-A200: #64ffda;
  --md-teal-A400: #1de9b6;
  --md-teal-A700: #00bfa5;
  --md-green-50: #e8f5e9;
  --md-green-100: #c8e6c9;
  --md-green-200: #a5d6a7;
  --md-green-300: #81c784;
  --md-green-400: #66bb6a;
  --md-green-500: #4caf50;
  --md-green-600: #43a047;
  --md-green-700: #388e3c;
  --md-green-800: #2e7d32;
  --md-green-900: #1b5e20;
  --md-green-A100: #b9f6ca;
  --md-green-A200: #69f0ae;
  --md-green-A400: #00e676;
  --md-green-A700: #00c853;
  --md-light-green-50: #f1f8e9;
  --md-light-green-100: #dcedc8;
  --md-light-green-200: #c5e1a5;
  --md-light-green-300: #aed581;
  --md-light-green-400: #9ccc65;
  --md-light-green-500: #8bc34a;
  --md-light-green-600: #7cb342;
  --md-light-green-700: #689f38;
  --md-light-green-800: #558b2f;
  --md-light-green-900: #33691e;
  --md-light-green-A100: #ccff90;
  --md-light-green-A200: #b2ff59;
  --md-light-green-A400: #76ff03;
  --md-light-green-A700: #64dd17;
  --md-lime-50: #f9fbe7;
  --md-lime-100: #f0f4c3;
  --md-lime-200: #e6ee9c;
  --md-lime-300: #dce775;
  --md-lime-400: #d4e157;
  --md-lime-500: #cddc39;
  --md-lime-600: #c0ca33;
  --md-lime-700: #afb42b;
  --md-lime-800: #9e9d24;
  --md-lime-900: #827717;
  --md-lime-A100: #f4ff81;
  --md-lime-A200: #eeff41;
  --md-lime-A400: #c6ff00;
  --md-lime-A700: #aeea00;
  --md-yellow-50: #fffde7;
  --md-yellow-100: #fff9c4;
  --md-yellow-200: #fff59d;
  --md-yellow-300: #fff176;
  --md-yellow-400: #ffee58;
  --md-yellow-500: #ffeb3b;
  --md-yellow-600: #fdd835;
  --md-yellow-700: #fbc02d;
  --md-yellow-800: #f9a825;
  --md-yellow-900: #f57f17;
  --md-yellow-A100: #ffff8d;
  --md-yellow-A200: #ff0;
  --md-yellow-A400: #ffea00;
  --md-yellow-A700: #ffd600;
  --md-amber-50: #fff8e1;
  --md-amber-100: #ffecb3;
  --md-amber-200: #ffe082;
  --md-amber-300: #ffd54f;
  --md-amber-400: #ffca28;
  --md-amber-500: #ffc107;
  --md-amber-600: #ffb300;
  --md-amber-700: #ffa000;
  --md-amber-800: #ff8f00;
  --md-amber-900: #ff6f00;
  --md-amber-A100: #ffe57f;
  --md-amber-A200: #ffd740;
  --md-amber-A400: #ffc400;
  --md-amber-A700: #ffab00;
  --md-orange-50: #fff3e0;
  --md-orange-100: #ffe0b2;
  --md-orange-200: #ffcc80;
  --md-orange-300: #ffb74d;
  --md-orange-400: #ffa726;
  --md-orange-500: #ff9800;
  --md-orange-600: #fb8c00;
  --md-orange-700: #f57c00;
  --md-orange-800: #ef6c00;
  --md-orange-900: #e65100;
  --md-orange-A100: #ffd180;
  --md-orange-A200: #ffab40;
  --md-orange-A400: #ff9100;
  --md-orange-A700: #ff6d00;
  --md-deep-orange-50: #fbe9e7;
  --md-deep-orange-100: #ffccbc;
  --md-deep-orange-200: #ffab91;
  --md-deep-orange-300: #ff8a65;
  --md-deep-orange-400: #ff7043;
  --md-deep-orange-500: #ff5722;
  --md-deep-orange-600: #f4511e;
  --md-deep-orange-700: #e64a19;
  --md-deep-orange-800: #d84315;
  --md-deep-orange-900: #bf360c;
  --md-deep-orange-A100: #ff9e80;
  --md-deep-orange-A200: #ff6e40;
  --md-deep-orange-A400: #ff3d00;
  --md-deep-orange-A700: #dd2c00;
  --md-brown-50: #efebe9;
  --md-brown-100: #d7ccc8;
  --md-brown-200: #bcaaa4;
  --md-brown-300: #a1887f;
  --md-brown-400: #8d6e63;
  --md-brown-500: #795548;
  --md-brown-600: #6d4c41;
  --md-brown-700: #5d4037;
  --md-brown-800: #4e342e;
  --md-brown-900: #3e2723;
  --md-grey-50: #fafafa;
  --md-grey-100: #f5f5f5;
  --md-grey-200: #eee;
  --md-grey-300: #e0e0e0;
  --md-grey-400: #bdbdbd;
  --md-grey-500: #9e9e9e;
  --md-grey-600: #757575;
  --md-grey-700: #616161;
  --md-grey-800: #424242;
  --md-grey-900: #212121;
  --md-blue-grey-50: #eceff1;
  --md-blue-grey-100: #cfd8dc;
  --md-blue-grey-200: #b0bec5;
  --md-blue-grey-300: #90a4ae;
  --md-blue-grey-400: #78909c;
  --md-blue-grey-500: #607d8b;
  --md-blue-grey-600: #546e7a;
  --md-blue-grey-700: #455a64;
  --md-blue-grey-800: #37474f;
  --md-blue-grey-900: #263238;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| RenderedText
|----------------------------------------------------------------------------*/

:root {
  /* This is the padding value to fill the gaps between lines containing spans with background color. */
  --jp-private-code-span-padding: calc(
    (var(--jp-code-line-height) - 1) * var(--jp-code-font-size) / 2
  );
}

.jp-RenderedText {
  text-align: left;
  padding-left: var(--jp-code-padding);
  line-height: var(--jp-code-line-height);
  font-family: var(--jp-code-font-family);
}

.jp-RenderedText pre,
.jp-RenderedJavaScript pre,
.jp-RenderedHTMLCommon pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
  border: none;
  margin: 0;
  padding: 0;
}

.jp-RenderedText pre a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

.jp-RenderedText pre a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}

.jp-RenderedText pre a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* console foregrounds and backgrounds */
.jp-RenderedText pre .ansi-black-fg {
  color: #3e424d;
}

.jp-RenderedText pre .ansi-red-fg {
  color: #e75c58;
}

.jp-RenderedText pre .ansi-green-fg {
  color: #00a250;
}

.jp-RenderedText pre .ansi-yellow-fg {
  color: #ddb62b;
}

.jp-RenderedText pre .ansi-blue-fg {
  color: #208ffb;
}

.jp-RenderedText pre .ansi-magenta-fg {
  color: #d160c4;
}

.jp-RenderedText pre .ansi-cyan-fg {
  color: #60c6c8;
}

.jp-RenderedText pre .ansi-white-fg {
  color: #c5c1b4;
}

.jp-RenderedText pre .ansi-black-bg {
  background-color: #3e424d;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-red-bg {
  background-color: #e75c58;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-green-bg {
  background-color: #00a250;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-yellow-bg {
  background-color: #ddb62b;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-blue-bg {
  background-color: #208ffb;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-magenta-bg {
  background-color: #d160c4;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-cyan-bg {
  background-color: #60c6c8;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-white-bg {
  background-color: #c5c1b4;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-black-intense-fg {
  color: #282c36;
}

.jp-RenderedText pre .ansi-red-intense-fg {
  color: #b22b31;
}

.jp-RenderedText pre .ansi-green-intense-fg {
  color: #007427;
}

.jp-RenderedText pre .ansi-yellow-intense-fg {
  color: #b27d12;
}

.jp-RenderedText pre .ansi-blue-intense-fg {
  color: #0065ca;
}

.jp-RenderedText pre .ansi-magenta-intense-fg {
  color: #a03196;
}

.jp-RenderedText pre .ansi-cyan-intense-fg {
  color: #258f8f;
}

.jp-RenderedText pre .ansi-white-intense-fg {
  color: #a1a6b2;
}

.jp-RenderedText pre .ansi-black-intense-bg {
  background-color: #282c36;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-red-intense-bg {
  background-color: #b22b31;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-green-intense-bg {
  background-color: #007427;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-yellow-intense-bg {
  background-color: #b27d12;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-blue-intense-bg {
  background-color: #0065ca;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-magenta-intense-bg {
  background-color: #a03196;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-cyan-intense-bg {
  background-color: #258f8f;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-white-intense-bg {
  background-color: #a1a6b2;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-default-inverse-fg {
  color: var(--jp-ui-inverse-font-color0);
}

.jp-RenderedText pre .ansi-default-inverse-bg {
  background-color: var(--jp-inverse-layout-color0);
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-bold {
  font-weight: bold;
}

.jp-RenderedText pre .ansi-underline {
  text-decoration: underline;
}

.jp-RenderedText[data-mime-type='application/vnd.jupyter.stderr'] {
  background: var(--jp-rendermime-error-background);
  padding-top: var(--jp-code-padding);
}

/*-----------------------------------------------------------------------------
| RenderedLatex
|----------------------------------------------------------------------------*/

.jp-RenderedLatex {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
}

/* Left-justify outputs.*/
.jp-OutputArea-output.jp-RenderedLatex {
  padding: var(--jp-code-padding);
  text-align: left;
}

/*-----------------------------------------------------------------------------
| RenderedHTML
|----------------------------------------------------------------------------*/

.jp-RenderedHTMLCommon {
  color: var(--jp-content-font-color1);
  font-family: var(--jp-content-font-family);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);

  /* Give a bit more R padding on Markdown text to keep line lengths reasonable */
  padding-right: 20px;
}

.jp-RenderedHTMLCommon em {
  font-style: italic;
}

.jp-RenderedHTMLCommon strong {
  font-weight: bold;
}

.jp-RenderedHTMLCommon u {
  text-decoration: underline;
}

.jp-RenderedHTMLCommon a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* Headings */

.jp-RenderedHTMLCommon h1,
.jp-RenderedHTMLCommon h2,
.jp-RenderedHTMLCommon h3,
.jp-RenderedHTMLCommon h4,
.jp-RenderedHTMLCommon h5,
.jp-RenderedHTMLCommon h6 {
  line-height: var(--jp-content-heading-line-height);
  font-weight: var(--jp-content-heading-font-weight);
  font-style: normal;
  margin: var(--jp-content-heading-margin-top) 0
    var(--jp-content-heading-margin-bottom) 0;
}

.jp-RenderedHTMLCommon h1:first-child,
.jp-RenderedHTMLCommon h2:first-child,
.jp-RenderedHTMLCommon h3:first-child,
.jp-RenderedHTMLCommon h4:first-child,
.jp-RenderedHTMLCommon h5:first-child,
.jp-RenderedHTMLCommon h6:first-child {
  margin-top: calc(0.5 * var(--jp-content-heading-margin-top));
}

.jp-RenderedHTMLCommon h1:last-child,
.jp-RenderedHTMLCommon h2:last-child,
.jp-RenderedHTMLCommon h3:last-child,
.jp-RenderedHTMLCommon h4:last-child,
.jp-RenderedHTMLCommon h5:last-child,
.jp-RenderedHTMLCommon h6:last-child {
  margin-bottom: calc(0.5 * var(--jp-content-heading-margin-bottom));
}

.jp-RenderedHTMLCommon h1 {
  font-size: var(--jp-content-font-size5);
}

.jp-RenderedHTMLCommon h2 {
  font-size: var(--jp-content-font-size4);
}

.jp-RenderedHTMLCommon h3 {
  font-size: var(--jp-content-font-size3);
}

.jp-RenderedHTMLCommon h4 {
  font-size: var(--jp-content-font-size2);
}

.jp-RenderedHTMLCommon h5 {
  font-size: var(--jp-content-font-size1);
}

.jp-RenderedHTMLCommon h6 {
  font-size: var(--jp-content-font-size0);
}

/* Lists */

/* stylelint-disable selector-max-type, selector-max-compound-selectors */

.jp-RenderedHTMLCommon ul:not(.list-inline),
.jp-RenderedHTMLCommon ol:not(.list-inline) {
  padding-left: 2em;
}

.jp-RenderedHTMLCommon ul {
  list-style: disc;
}

.jp-RenderedHTMLCommon ul ul {
  list-style: square;
}

.jp-RenderedHTMLCommon ul ul ul {
  list-style: circle;
}

.jp-RenderedHTMLCommon ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol ol {
  list-style: upper-alpha;
}

.jp-RenderedHTMLCommon ol ol ol {
  list-style: lower-alpha;
}

.jp-RenderedHTMLCommon ol ol ol ol {
  list-style: lower-roman;
}

.jp-RenderedHTMLCommon ol ol ol ol ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol,
.jp-RenderedHTMLCommon ul {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon ul ul,
.jp-RenderedHTMLCommon ul ol,
.jp-RenderedHTMLCommon ol ul,
.jp-RenderedHTMLCommon ol ol {
  margin-bottom: 0;
}

/* stylelint-enable selector-max-type, selector-max-compound-selectors */

.jp-RenderedHTMLCommon hr {
  color: var(--jp-border-color2);
  background-color: var(--jp-border-color1);
  margin-top: 1em;
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon > pre {
  margin: 1.5em 2em;
}

.jp-RenderedHTMLCommon pre,
.jp-RenderedHTMLCommon code {
  border: 0;
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  line-height: var(--jp-code-line-height);
  padding: 0;
  white-space: pre-wrap;
}

.jp-RenderedHTMLCommon :not(pre) > code {
  background-color: var(--jp-layout-color2);
  padding: 1px 5px;
}

/* Tables */

.jp-RenderedHTMLCommon table {
  border-collapse: collapse;
  border-spacing: 0;
  border: none;
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  table-layout: fixed;
  margin-left: auto;
  margin-bottom: 1em;
  margin-right: auto;
}

.jp-RenderedHTMLCommon thead {
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  vertical-align: bottom;
}

.jp-RenderedHTMLCommon td,
.jp-RenderedHTMLCommon th,
.jp-RenderedHTMLCommon tr {
  vertical-align: middle;
  padding: 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}

.jp-RenderedMarkdown.jp-RenderedHTMLCommon td,
.jp-RenderedMarkdown.jp-RenderedHTMLCommon th {
  max-width: none;
}

:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon td,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon th,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon tr {
  text-align: right;
}

.jp-RenderedHTMLCommon th {
  font-weight: bold;
}

.jp-RenderedHTMLCommon tbody tr:nth-child(odd) {
  background: var(--jp-layout-color0);
}

.jp-RenderedHTMLCommon tbody tr:nth-child(even) {
  background: var(--jp-rendermime-table-row-background);
}

.jp-RenderedHTMLCommon tbody tr:hover {
  background: var(--jp-rendermime-table-row-hover-background);
}

.jp-RenderedHTMLCommon p {
  text-align: left;
  margin: 0;
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon img {
  -moz-force-broken-image-icon: 1;
}

/* Restrict to direct children as other images could be nested in other content. */
.jp-RenderedHTMLCommon > img {
  display: block;
  margin-left: 0;
  margin-right: 0;
  margin-bottom: 1em;
}

/* Change color behind transparent images if they need it... */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-light-background {
  background-color: var(--jp-inverse-layout-color1);
}

[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-dark-background {
  background-color: var(--jp-inverse-layout-color1);
}

.jp-RenderedHTMLCommon img,
.jp-RenderedImage img,
.jp-RenderedHTMLCommon svg,
.jp-RenderedSVG svg {
  max-width: 100%;
  height: auto;
}

.jp-RenderedHTMLCommon img.jp-mod-unconfined,
.jp-RenderedImage img.jp-mod-unconfined,
.jp-RenderedHTMLCommon svg.jp-mod-unconfined,
.jp-RenderedSVG svg.jp-mod-unconfined {
  max-width: none;
}

.jp-RenderedHTMLCommon .alert {
  padding: var(--jp-notebook-padding);
  border: var(--jp-border-width) solid transparent;
  border-radius: var(--jp-border-radius);
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon .alert-info {
  color: var(--jp-info-color0);
  background-color: var(--jp-info-color3);
  border-color: var(--jp-info-color2);
}

.jp-RenderedHTMLCommon .alert-info hr {
  border-color: var(--jp-info-color3);
}

.jp-RenderedHTMLCommon .alert-info > p:last-child,
.jp-RenderedHTMLCommon .alert-info > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-warning {
  color: var(--jp-warn-color0);
  background-color: var(--jp-warn-color3);
  border-color: var(--jp-warn-color2);
}

.jp-RenderedHTMLCommon .alert-warning hr {
  border-color: var(--jp-warn-color3);
}

.jp-RenderedHTMLCommon .alert-warning > p:last-child,
.jp-RenderedHTMLCommon .alert-warning > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-success {
  color: var(--jp-success-color0);
  background-color: var(--jp-success-color3);
  border-color: var(--jp-success-color2);
}

.jp-RenderedHTMLCommon .alert-success hr {
  border-color: var(--jp-success-color3);
}

.jp-RenderedHTMLCommon .alert-success > p:last-child,
.jp-RenderedHTMLCommon .alert-success > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-danger {
  color: var(--jp-error-color0);
  background-color: var(--jp-error-color3);
  border-color: var(--jp-error-color2);
}

.jp-RenderedHTMLCommon .alert-danger hr {
  border-color: var(--jp-error-color3);
}

.jp-RenderedHTMLCommon .alert-danger > p:last-child,
.jp-RenderedHTMLCommon .alert-danger > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon blockquote {
  margin: 1em 2em;
  padding: 0 1em;
  border-left: 5px solid var(--jp-border-color2);
}

a.jp-InternalAnchorLink {
  visibility: hidden;
  margin-left: 8px;
  color: var(--md-blue-800);
}

h1:hover .jp-InternalAnchorLink,
h2:hover .jp-InternalAnchorLink,
h3:hover .jp-InternalAnchorLink,
h4:hover .jp-InternalAnchorLink,
h5:hover .jp-InternalAnchorLink,
h6:hover .jp-InternalAnchorLink {
  visibility: visible;
}

.jp-RenderedHTMLCommon kbd {
  background-color: var(--jp-rendermime-table-row-background);
  border: 1px solid var(--jp-border-color0);
  border-bottom-color: var(--jp-border-color2);
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
  display: inline-block;
  font-size: var(--jp-ui-font-size0);
  line-height: 1em;
  padding: 0.2em 0.5em;
}

/* Most direct children of .jp-RenderedHTMLCommon have a margin-bottom of 1.0.
 * At the bottom of cells this is a bit too much as there is also spacing
 * between cells. Going all the way to 0 gets too tight between markdown and
 * code cells.
 */
.jp-RenderedHTMLCommon > *:last-child {
  margin-bottom: 0.5em;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-cursor-backdrop {
  position: fixed;
  width: 200px;
  height: 200px;
  margin-top: -100px;
  margin-left: -100px;
  will-change: transform;
  z-index: 100;
}

.lm-mod-drag-image {
  will-change: transform;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-lineFormSearch {
  padding: 4px 12px;
  background-color: var(--jp-layout-color2);
  box-shadow: var(--jp-toolbar-box-shadow);
  z-index: 2;
  font-size: var(--jp-ui-font-size1);
}

.jp-lineFormCaption {
  font-size: var(--jp-ui-font-size0);
  line-height: var(--jp-ui-font-size1);
  margin-top: 4px;
  color: var(--jp-ui-font-color0);
}

.jp-baseLineForm {
  border: none;
  border-radius: 0;
  position: absolute;
  background-size: 16px;
  background-repeat: no-repeat;
  background-position: center;
  outline: none;
}

.jp-lineFormButtonContainer {
  top: 4px;
  right: 8px;
  height: 24px;
  padding: 0 12px;
  width: 12px;
}

.jp-lineFormButtonIcon {
  top: 0;
  right: 0;
  background-color: var(--jp-brand-color1);
  height: 100%;
  width: 100%;
  box-sizing: border-box;
  padding: 4px 6px;
}

.jp-lineFormButton {
  top: 0;
  right: 0;
  background-color: transparent;
  height: 100%;
  width: 100%;
  box-sizing: border-box;
}

.jp-lineFormWrapper {
  overflow: hidden;
  padding: 0 8px;
  border: 1px solid var(--jp-border-color0);
  background-color: var(--jp-input-active-background);
  height: 22px;
}

.jp-lineFormWrapperFocusWithin {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-lineFormInput {
  background: transparent;
  width: 200px;
  height: 100%;
  border: none;
  outline: none;
  color: var(--jp-ui-font-color0);
  line-height: 28px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-JSONEditor {
  display: flex;
  flex-direction: column;
  width: 100%;
}

.jp-JSONEditor-host {
  flex: 1 1 auto;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0;
  background: var(--jp-layout-color0);
  min-height: 50px;
  padding: 1px;
}

.jp-JSONEditor.jp-mod-error .jp-JSONEditor-host {
  border-color: red;
  outline-color: red;
}

.jp-JSONEditor-header {
  display: flex;
  flex: 1 0 auto;
  padding: 0 0 0 12px;
}

.jp-JSONEditor-header label {
  flex: 0 0 auto;
}

.jp-JSONEditor-commitButton {
  height: 16px;
  width: 16px;
  background-size: 18px;
  background-repeat: no-repeat;
  background-position: center;
}

.jp-JSONEditor-host.jp-mod-focused {
  background-color: var(--jp-input-active-background);
  border: 1px solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

.jp-Editor.jp-mod-dropTarget {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/
.jp-DocumentSearch-input {
  border: none;
  outline: none;
  color: var(--jp-ui-font-color0);
  font-size: var(--jp-ui-font-size1);
  background-color: var(--jp-layout-color0);
  font-family: var(--jp-ui-font-family);
  padding: 2px 1px;
  resize: none;
}

.jp-DocumentSearch-overlay {
  position: absolute;
  background-color: var(--jp-toolbar-background);
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  border-left: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  top: 0;
  right: 0;
  z-index: 7;
  min-width: 405px;
  padding: 2px;
  font-size: var(--jp-ui-font-size1);

  --jp-private-document-search-button-height: 20px;
}

.jp-DocumentSearch-overlay button {
  background-color: var(--jp-toolbar-background);
  outline: 0;
}

.jp-DocumentSearch-overlay button:hover {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-overlay button:active {
  background-color: var(--jp-layout-color3);
}

.jp-DocumentSearch-overlay-row {
  display: flex;
  align-items: center;
  margin-bottom: 2px;
}

.jp-DocumentSearch-button-content {
  display: inline-block;
  cursor: pointer;
  box-sizing: border-box;
  width: 100%;
  height: 100%;
}

.jp-DocumentSearch-button-content svg {
  width: 100%;
  height: 100%;
}

.jp-DocumentSearch-input-wrapper {
  border: var(--jp-border-width) solid var(--jp-border-color0);
  display: flex;
  background-color: var(--jp-layout-color0);
  margin: 2px;
}

.jp-DocumentSearch-input-wrapper:focus-within {
  border-color: var(--jp-cell-editor-active-border-color);
}

.jp-DocumentSearch-toggle-wrapper,
.jp-DocumentSearch-button-wrapper {
  all: initial;
  overflow: hidden;
  display: inline-block;
  border: none;
  box-sizing: border-box;
}

.jp-DocumentSearch-toggle-wrapper {
  width: 14px;
  height: 14px;
}

.jp-DocumentSearch-button-wrapper {
  width: var(--jp-private-document-search-button-height);
  height: var(--jp-private-document-search-button-height);
}

.jp-DocumentSearch-toggle-wrapper:focus,
.jp-DocumentSearch-button-wrapper:focus {
  outline: var(--jp-border-width) solid
    var(--jp-cell-editor-active-border-color);
  outline-offset: -1px;
}

.jp-DocumentSearch-toggle-wrapper,
.jp-DocumentSearch-button-wrapper,
.jp-DocumentSearch-button-content:focus {
  outline: none;
}

.jp-DocumentSearch-toggle-placeholder {
  width: 5px;
}

.jp-DocumentSearch-input-button::before {
  display: block;
  padding-top: 100%;
}

.jp-DocumentSearch-input-button-off {
  opacity: var(--jp-search-toggle-off-opacity);
}

.jp-DocumentSearch-input-button-off:hover {
  opacity: var(--jp-search-toggle-hover-opacity);
}

.jp-DocumentSearch-input-button-on {
  opacity: var(--jp-search-toggle-on-opacity);
}

.jp-DocumentSearch-index-counter {
  padding-left: 10px;
  padding-right: 10px;
  user-select: none;
  min-width: 35px;
  display: inline-block;
}

.jp-DocumentSearch-up-down-wrapper {
  display: inline-block;
  padding-right: 2px;
  margin-left: auto;
  white-space: nowrap;
}

.jp-DocumentSearch-spacer {
  margin-left: auto;
}

.jp-DocumentSearch-up-down-wrapper button {
  outline: 0;
  border: none;
  width: var(--jp-private-document-search-button-height);
  height: var(--jp-private-document-search-button-height);
  vertical-align: middle;
  margin: 1px 5px 2px;
}

.jp-DocumentSearch-up-down-button:hover {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-up-down-button:active {
  background-color: var(--jp-layout-color3);
}

.jp-DocumentSearch-filter-button {
  border-radius: var(--jp-border-radius);
}

.jp-DocumentSearch-filter-button:hover {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-filter-button-enabled {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-filter-button-enabled:hover {
  background-color: var(--jp-layout-color3);
}

.jp-DocumentSearch-search-options {
  padding: 0 8px;
  margin-left: 3px;
  width: 100%;
  display: grid;
  justify-content: start;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  justify-items: stretch;
}

.jp-DocumentSearch-search-filter-disabled {
  color: var(--jp-ui-font-color2);
}

.jp-DocumentSearch-search-filter {
  display: flex;
  align-items: center;
  user-select: none;
}

.jp-DocumentSearch-regex-error {
  color: var(--jp-error-color0);
}

.jp-DocumentSearch-replace-button-wrapper {
  overflow: hidden;
  display: inline-block;
  box-sizing: border-box;
  border: var(--jp-border-width) solid var(--jp-border-color0);
  margin: auto 2px;
  padding: 1px 4px;
  height: calc(var(--jp-private-document-search-button-height) + 2px);
}

.jp-DocumentSearch-replace-button-wrapper:focus {
  border: var(--jp-border-width) solid var(--jp-cell-editor-active-border-color);
}

.jp-DocumentSearch-replace-button {
  display: inline-block;
  text-align: center;
  cursor: pointer;
  box-sizing: border-box;
  color: var(--jp-ui-font-color1);

  /* height - 2 * (padding of wrapper) */
  line-height: calc(var(--jp-private-document-search-button-height) - 2px);
  width: 100%;
  height: 100%;
}

.jp-DocumentSearch-replace-button:focus {
  outline: none;
}

.jp-DocumentSearch-replace-wrapper-class {
  margin-left: 14px;
  display: flex;
}

.jp-DocumentSearch-replace-toggle {
  border: none;
  background-color: var(--jp-toolbar-background);
  border-radius: var(--jp-border-radius);
}

.jp-DocumentSearch-replace-toggle:hover {
  background-color: var(--jp-layout-color2);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.cm-editor {
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  border: 0;
  border-radius: 0;
  height: auto;

  /* Changed to auto to autogrow */
}

.cm-editor pre {
  padding: 0 var(--jp-code-padding);
}

.jp-CodeMirrorEditor[data-type='inline'] .cm-dialog {
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

.jp-CodeMirrorEditor {
  cursor: text;
}

/* When zoomed out 67% and 33% on a screen of 1440 width x 900 height */
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .jp-CodeMirrorEditor[data-type='inline'] .cm-cursor {
    border-left: var(--jp-code-cursor-width1) solid
      var(--jp-editor-cursor-color);
  }
}

/* When zoomed out less than 33% */
@media screen and (min-width: 4320px) {
  .jp-CodeMirrorEditor[data-type='inline'] .cm-cursor {
    border-left: var(--jp-code-cursor-width2) solid
      var(--jp-editor-cursor-color);
  }
}

.cm-editor.jp-mod-readOnly .cm-cursor {
  display: none;
}

.jp-CollaboratorCursor {
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-top: none;
  border-bottom: 3px solid;
  background-clip: content-box;
  margin-left: -5px;
  margin-right: -5px;
}

.cm-searching,
.cm-searching span {
  /* `.cm-searching span`: we need to override syntax highlighting */
  background-color: var(--jp-search-unselected-match-background-color);
  color: var(--jp-search-unselected-match-color);
}

.cm-searching::selection,
.cm-searching span::selection {
  background-color: var(--jp-search-unselected-match-background-color);
  color: var(--jp-search-unselected-match-color);
}

.jp-current-match > .cm-searching,
.jp-current-match > .cm-searching span,
.cm-searching > .jp-current-match,
.cm-searching > .jp-current-match span {
  background-color: var(--jp-search-selected-match-background-color);
  color: var(--jp-search-selected-match-color);
}

.jp-current-match > .cm-searching::selection,
.cm-searching > .jp-current-match::selection,
.jp-current-match > .cm-searching span::selection {
  background-color: var(--jp-search-selected-match-background-color);
  color: var(--jp-search-selected-match-color);
}

.cm-trailingspace {
  background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAgAAAAFCAYAAAB4ka1VAAAAsElEQVQIHQGlAFr/AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA7+r3zKmT0/+pk9P/7+r3zAAAAAAAAAAABAAAAAAAAAAA6OPzM+/q9wAAAAAA6OPzMwAAAAAAAAAAAgAAAAAAAAAAGR8NiRQaCgAZIA0AGR8NiQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQyoYJ/SY80UAAAAASUVORK5CYII=);
  background-position: center left;
  background-repeat: repeat-x;
}

.jp-CollaboratorCursor-hover {
  position: absolute;
  z-index: 1;
  transform: translateX(-50%);
  color: white;
  border-radius: 3px;
  padding-left: 4px;
  padding-right: 4px;
  padding-top: 1px;
  padding-bottom: 1px;
  text-align: center;
  font-size: var(--jp-ui-font-size1);
  white-space: nowrap;
}

.jp-CodeMirror-ruler {
  border-left: 1px dashed var(--jp-border-color2);
}

/* Styles for shared cursors (remote cursor locations and selected ranges) */
.jp-CodeMirrorEditor .cm-ySelectionCaret {
  position: relative;
  border-left: 1px solid black;
  margin-left: -1px;
  margin-right: -1px;
  box-sizing: border-box;
}

.jp-CodeMirrorEditor .cm-ySelectionCaret > .cm-ySelectionInfo {
  white-space: nowrap;
  position: absolute;
  top: -1.15em;
  padding-bottom: 0.05em;
  left: -1px;
  font-size: 0.95em;
  font-family: var(--jp-ui-font-family);
  font-weight: bold;
  line-height: normal;
  user-select: none;
  color: white;
  padding-left: 2px;
  padding-right: 2px;
  z-index: 101;
  transition: opacity 0.3s ease-in-out;
}

.jp-CodeMirrorEditor .cm-ySelectionInfo {
  transition-delay: 0.7s;
  opacity: 0;
}

.jp-CodeMirrorEditor .cm-ySelectionCaret:hover > .cm-ySelectionInfo {
  opacity: 1;
  transition-delay: 0s;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MimeDocument {
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-filebrowser-button-height: 28px;
  --jp-private-filebrowser-button-width: 48px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-FileBrowser .jp-SidePanel-content {
  display: flex;
  flex-direction: column;
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  flex-wrap: wrap;
  row-gap: 12px;
  border-bottom: none;
  height: auto;
  margin: 8px 12px 0;
  box-shadow: none;
  padding: 0;
  justify-content: flex-start;
}

.jp-FileBrowser-Panel {
  flex: 1 1 auto;
  display: flex;
  flex-direction: column;
}

.jp-BreadCrumbs {
  flex: 0 0 auto;
  margin: 8px 12px;
}

.jp-BreadCrumbs-item {
  margin: 0 2px;
  padding: 0 2px;
  border-radius: var(--jp-border-radius);
  cursor: pointer;
}

.jp-BreadCrumbs-item:hover {
  background-color: var(--jp-layout-color2);
}

.jp-BreadCrumbs-item:first-child {
  margin-left: 0;
}

.jp-BreadCrumbs-item.jp-mod-dropTarget {
  background-color: var(--jp-brand-color2);
  opacity: 0.7;
}

/*-----------------------------------------------------------------------------
| Buttons
|----------------------------------------------------------------------------*/

.jp-FileBrowser-toolbar > .jp-Toolbar-item {
  flex: 0 0 auto;
  padding-left: 0;
  padding-right: 2px;
  align-items: center;
  height: unset;
}

.jp-FileBrowser-toolbar > .jp-Toolbar-item .jp-ToolbarButtonComponent {
  width: 40px;
}

/*-----------------------------------------------------------------------------
| Other styles
|----------------------------------------------------------------------------*/

.jp-FileDialog.jp-mod-conflict input {
  color: var(--jp-error-color1);
}

.jp-FileDialog .jp-new-name-title {
  margin-top: 12px;
}

.jp-LastModified-hidden {
  display: none;
}

.jp-FileSize-hidden {
  display: none;
}

.jp-FileBrowser .lm-AccordionPanel > h3:first-child {
  display: none;
}

/*-----------------------------------------------------------------------------
| DirListing
|----------------------------------------------------------------------------*/

.jp-DirListing {
  flex: 1 1 auto;
  display: flex;
  flex-direction: column;
  outline: 0;
}

.jp-DirListing-header {
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  align-items: center;
  overflow: hidden;
  border-top: var(--jp-border-width) solid var(--jp-border-color2);
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  box-shadow: var(--jp-toolbar-box-shadow);
  z-index: 2;
}

.jp-DirListing-headerItem {
  padding: 4px 12px 2px;
  font-weight: 500;
}

.jp-DirListing-headerItem:hover {
  background: var(--jp-layout-color2);
}

.jp-DirListing-headerItem.jp-id-name {
  flex: 1 0 84px;
}

.jp-DirListing-headerItem.jp-id-modified {
  flex: 0 0 112px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
}

.jp-DirListing-headerItem.jp-id-filesize {
  flex: 0 0 75px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
}

.jp-id-narrow {
  display: none;
  flex: 0 0 5px;
  padding: 4px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
  color: var(--jp-border-color2);
}

.jp-DirListing-narrow .jp-id-narrow {
  display: block;
}

.jp-DirListing-narrow .jp-id-modified,
.jp-DirListing-narrow .jp-DirListing-itemModified {
  display: none;
}

.jp-DirListing-headerItem.jp-mod-selected {
  font-weight: 600;
}

/* increase specificity to override bundled default */
.jp-DirListing-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

.jp-DirListing-content mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.jp-DirListing-content .jp-DirListing-item.jp-mod-selected mark {
  color: var(--jp-ui-inverse-font-color0);
}

/* Style the directory listing content when a user drops a file to upload */
.jp-DirListing.jp-mod-native-drop .jp-DirListing-content {
  outline: 5px dashed rgba(128, 128, 128, 0.5);
  outline-offset: -10px;
  cursor: copy;
}

.jp-DirListing-item {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 4px 12px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-DirListing-checkboxWrapper {
  /* Increases hit area of checkbox. */
  padding: 4px;
}

.jp-DirListing-header
  .jp-DirListing-checkboxWrapper
  + .jp-DirListing-headerItem {
  padding-left: 4px;
}

.jp-DirListing-content .jp-DirListing-checkboxWrapper {
  position: relative;
  left: -4px;
  margin: -4px 0 -4px -8px;
}

.jp-DirListing-checkboxWrapper.jp-mod-visible {
  visibility: visible;
}

/* For devices that support hovering, hide checkboxes until hovered, selected...
*/
@media (hover: hover) {
  .jp-DirListing-checkboxWrapper {
    visibility: hidden;
  }

  .jp-DirListing-item:hover .jp-DirListing-checkboxWrapper,
  .jp-DirListing-item.jp-mod-selected .jp-DirListing-checkboxWrapper {
    visibility: visible;
  }
}

.jp-DirListing-item[data-is-dot] {
  opacity: 75%;
}

.jp-DirListing-item.jp-mod-selected {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.jp-DirListing-item.jp-mod-dropTarget {
  background: var(--jp-brand-color3);
}

.jp-DirListing-item:hover:not(.jp-mod-selected) {
  background: var(--jp-layout-color2);
}

.jp-DirListing-itemIcon {
  flex: 0 0 20px;
  margin-right: 4px;
}

.jp-DirListing-itemText {
  flex: 1 0 64px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  user-select: none;
}

.jp-DirListing-itemText:focus {
  outline-width: 2px;
  outline-color: var(--jp-inverse-layout-color1);
  outline-style: solid;
  outline-offset: 1px;
}

.jp-DirListing-item.jp-mod-selected .jp-DirListing-itemText:focus {
  outline-color: var(--jp-layout-color1);
}

.jp-DirListing-itemModified {
  flex: 0 0 125px;
  text-align: right;
}

.jp-DirListing-itemFileSize {
  flex: 0 0 90px;
  text-align: right;
}

.jp-DirListing-editor {
  flex: 1 0 64px;
  outline: none;
  border: none;
  color: var(--jp-ui-font-color1);
  background-color: var(--jp-layout-color1);
}

.jp-DirListing-item.jp-mod-running .jp-DirListing-itemIcon::before {
  color: var(--jp-success-color1);
  content: '\25CF';
  font-size: 8px;
  position: absolute;
  left: -8px;
}

.jp-DirListing-item.jp-mod-running.jp-mod-selected
  .jp-DirListing-itemIcon::before {
  color: var(--jp-ui-inverse-font-color1);
}

.jp-DirListing-item.lm-mod-drag-image,
.jp-DirListing-item.jp-mod-selected.lm-mod-drag-image {
  font-size: var(--jp-ui-font-size1);
  padding-left: 4px;
  margin-left: 4px;
  width: 160px;
  background-color: var(--jp-ui-inverse-font-color2);
  box-shadow: var(--jp-elevation-z2);
  border-radius: 0;
  color: var(--jp-ui-font-color1);
  transform: translateX(-40%) translateY(-58%);
}

.jp-Document {
  min-width: 120px;
  min-height: 120px;
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Main OutputArea
| OutputArea has a list of Outputs
|----------------------------------------------------------------------------*/

.jp-OutputArea {
  overflow-y: auto;
}

.jp-OutputArea-child {
  display: table;
  table-layout: fixed;
  width: 100%;
  overflow: hidden;
}

.jp-OutputPrompt {
  width: var(--jp-cell-prompt-width);
  color: var(--jp-cell-outprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);

  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;

  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-OutputArea-prompt {
  display: table-cell;
  vertical-align: top;
}

.jp-OutputArea-output {
  display: table-cell;
  width: 100%;
  height: auto;
  overflow: auto;
  user-select: text;
  -moz-user-select: text;
  -webkit-user-select: text;
  -ms-user-select: text;
}

.jp-OutputArea .jp-RenderedText {
  padding-left: 1ch;
}

/**
 * Prompt overlay.
 */

.jp-OutputArea-promptOverlay {
  position: absolute;
  top: 0;
  width: var(--jp-cell-prompt-width);
  height: 100%;
  opacity: 0.5;
}

.jp-OutputArea-promptOverlay:hover {
  background: var(--jp-layout-color2);
  box-shadow: inset 0 0 1px var(--jp-inverse-layout-color0);
  cursor: zoom-out;
}

.jp-mod-outputsScrolled .jp-OutputArea-promptOverlay:hover {
  cursor: zoom-in;
}

/**
 * Isolated output.
 */
.jp-OutputArea-output.jp-mod-isolated {
  width: 100%;
  display: block;
}

/*
When drag events occur, `lm-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated {
  position: relative;
}

body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/* pre */

.jp-OutputArea-output pre {
  border: none;
  margin: 0;
  padding: 0;
  overflow-x: auto;
  overflow-y: auto;
  word-break: break-all;
  word-wrap: break-word;
  white-space: pre-wrap;
}

/* tables */

.jp-OutputArea-output.jp-RenderedHTMLCommon table {
  margin-left: 0;
  margin-right: 0;
}

/* description lists */

.jp-OutputArea-output dl,
.jp-OutputArea-output dt,
.jp-OutputArea-output dd {
  display: block;
}

.jp-OutputArea-output dl {
  width: 100%;
  overflow: hidden;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dt {
  font-weight: bold;
  float: left;
  width: 20%;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dd {
  float: left;
  width: 80%;
  padding: 0;
  margin: 0;
}

.jp-TrimmedOutputs pre {
  background: var(--jp-layout-color3);
  font-size: calc(var(--jp-code-font-size) * 1.4);
  text-align: center;
  text-transform: uppercase;
}

/* Hide the gutter in case of
 *  - nested output areas (e.g. in the case of output widgets)
 *  - mirrored output areas
 */
.jp-OutputArea .jp-OutputArea .jp-OutputArea-prompt {
  display: none;
}

/* Hide empty lines in the output area, for instance due to cleared widgets */
.jp-OutputArea-prompt:empty {
  padding: 0;
  border: 0;
}

/*-----------------------------------------------------------------------------
| executeResult is added to any Output-result for the display of the object
| returned by a cell
|----------------------------------------------------------------------------*/

.jp-OutputArea-output.jp-OutputArea-executeResult {
  margin-left: 0;
  width: 100%;
}

/* Text output with the Out[] prompt needs a top padding to match the
 * alignment of the Out[] prompt itself.
 */
.jp-OutputArea-executeResult .jp-RenderedText.jp-OutputArea-output {
  padding-top: var(--jp-code-padding);
  border-top: var(--jp-border-width) solid transparent;
}

/*-----------------------------------------------------------------------------
| The Stdin output
|----------------------------------------------------------------------------*/

.jp-Stdin-prompt {
  color: var(--jp-content-font-color0);
  padding-right: var(--jp-code-padding);
  vertical-align: baseline;
  flex: 0 0 auto;
}

.jp-Stdin-input {
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  color: inherit;
  background-color: inherit;
  width: 42%;
  min-width: 200px;

  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;

  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0 0.25em;
  margin: 0 0.25em;
  flex: 0 0 70%;
}

.jp-Stdin-input::placeholder {
  opacity: 0;
}

.jp-Stdin-input:focus {
  box-shadow: none;
}

.jp-Stdin-input:focus::placeholder {
  opacity: 1;
}

/*-----------------------------------------------------------------------------
| Output Area View
|----------------------------------------------------------------------------*/

.jp-LinkedOutputView .jp-OutputArea {
  height: 100%;
  display: block;
}

.jp-LinkedOutputView .jp-OutputArea-output:only-child {
  height: 100%;
}

/*-----------------------------------------------------------------------------
| Printing
|----------------------------------------------------------------------------*/

@media print {
  .jp-OutputArea-child {
    break-inside: avoid-page;
  }
}

/*-----------------------------------------------------------------------------
| Mobile
|----------------------------------------------------------------------------*/
@media only screen and (max-width: 760px) {
  .jp-OutputPrompt {
    display: table-row;
    text-align: left;
  }

  .jp-OutputArea-child .jp-OutputArea-output {
    display: table-row;
    margin-left: var(--jp-notebook-padding);
  }
}

/* Trimmed outputs warning */
.jp-TrimmedOutputs > a {
  margin: 10px;
  text-decoration: none;
  cursor: pointer;
}

.jp-TrimmedOutputs > a:hover {
  text-decoration: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Table of Contents
|----------------------------------------------------------------------------*/

:root {
  --jp-private-toc-active-width: 4px;
}

.jp-TableOfContents {
  display: flex;
  flex-direction: column;
  background: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  height: 100%;
}

.jp-TableOfContents-placeholder {
  text-align: center;
}

.jp-TableOfContents-placeholderContent {
  color: var(--jp-content-font-color2);
  padding: 8px;
}

.jp-TableOfContents-placeholderContent > h3 {
  margin-bottom: var(--jp-content-heading-margin-bottom);
}

.jp-TableOfContents .jp-SidePanel-content {
  overflow-y: auto;
}

.jp-TableOfContents-tree {
  margin: 4px;
}

.jp-TableOfContents ol {
  list-style-type: none;
}

/* stylelint-disable-next-line selector-max-type */
.jp-TableOfContents li > ol {
  /* Align left border with triangle icon center */
  padding-left: 11px;
}

.jp-TableOfContents-content {
  /* left margin for the active heading indicator */
  margin: 0 0 0 var(--jp-private-toc-active-width);
  padding: 0;
  background-color: var(--jp-layout-color1);
}

.jp-tocItem {
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-tocItem-heading {
  display: flex;
  cursor: pointer;
}

.jp-tocItem-heading:hover {
  background-color: var(--jp-layout-color2);
}

.jp-tocItem-content {
  display: block;
  padding: 4px 0;
  white-space: nowrap;
  text-overflow: ellipsis;
  overflow-x: hidden;
}

.jp-tocItem-collapser {
  height: 20px;
  margin: 2px 2px 0;
  padding: 0;
  background: none;
  border: none;
  cursor: pointer;
}

.jp-tocItem-collapser:hover {
  background-color: var(--jp-layout-color3);
}

/* Active heading indicator */

.jp-tocItem-heading::before {
  content: ' ';
  background: transparent;
  width: var(--jp-private-toc-active-width);
  height: 24px;
  position: absolute;
  left: 0;
  border-radius: var(--jp-border-radius);
}

.jp-tocItem-heading.jp-tocItem-active::before {
  background-color: var(--jp-brand-color1);
}

.jp-tocItem-heading:hover.jp-tocItem-active::before {
  background: var(--jp-brand-color0);
  opacity: 1;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapser {
  flex: 0 0 var(--jp-cell-collapser-width);
  padding: 0;
  margin: 0;
  border: none;
  outline: none;
  background: transparent;
  border-radius: var(--jp-border-radius);
  opacity: 1;
}

.jp-Collapser-child {
  display: block;
  width: 100%;
  box-sizing: border-box;

  /* height: 100% doesn't work because the height of its parent is computed from content */
  position: absolute;
  top: 0;
  bottom: 0;
}

/*-----------------------------------------------------------------------------
| Printing
|----------------------------------------------------------------------------*/

/*
Hiding collapsers in print mode.

Note: input and output wrappers have "display: block" propery in print mode.
*/

@media print {
  .jp-Collapser {
    display: none;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Header/Footer
|----------------------------------------------------------------------------*/

/* Hidden by zero height by default */
.jp-CellHeader,
.jp-CellFooter {
  height: 0;
  width: 100%;
  padding: 0;
  margin: 0;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Input
|----------------------------------------------------------------------------*/

/* All input areas */
.jp-InputArea {
  display: table;
  table-layout: fixed;
  width: 100%;
  overflow: hidden;
}

.jp-InputArea-editor {
  display: table-cell;
  overflow: hidden;
  vertical-align: top;

  /* This is the non-active, default styling */
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0;
  background: var(--jp-cell-editor-background);
}

.jp-InputPrompt {
  display: table-cell;
  vertical-align: top;
  width: var(--jp-cell-prompt-width);
  color: var(--jp-cell-inprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  opacity: var(--jp-cell-prompt-opacity);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;

  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;

  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

/*-----------------------------------------------------------------------------
| Mobile
|----------------------------------------------------------------------------*/
@media only screen and (max-width: 760px) {
  .jp-InputArea-editor {
    display: table-row;
    margin-left: var(--jp-notebook-padding);
  }

  .jp-InputPrompt {
    display: table-row;
    text-align: left;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Placeholder {
  display: table;
  table-layout: fixed;
  width: 100%;
}

.jp-Placeholder-prompt {
  display: table-cell;
  box-sizing: border-box;
}

.jp-Placeholder-content {
  display: table-cell;
  padding: 4px 6px;
  border: 1px solid transparent;
  border-radius: 0;
  background: none;
  box-sizing: border-box;
  cursor: pointer;
}

.jp-Placeholder-contentContainer {
  display: flex;
}

.jp-Placeholder-content:hover,
.jp-InputPlaceholder > .jp-Placeholder-content:hover {
  border-color: var(--jp-layout-color3);
}

.jp-Placeholder-content .jp-MoreHorizIcon {
  width: 32px;
  height: 16px;
  border: 1px solid transparent;
  border-radius: var(--jp-border-radius);
}

.jp-Placeholder-content .jp-MoreHorizIcon:hover {
  border: 1px solid var(--jp-border-color1);
  box-shadow: 0 0 2px 0 rgba(0, 0, 0, 0.25);
  background-color: var(--jp-layout-color0);
}

.jp-PlaceholderText {
  white-space: nowrap;
  overflow-x: hidden;
  color: var(--jp-inverse-layout-color3);
  font-family: var(--jp-code-font-family);
}

.jp-InputPlaceholder > .jp-Placeholder-content {
  border-color: var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-cell-scrolling-output-offset: 5px;
}

/*-----------------------------------------------------------------------------
| Cell
|----------------------------------------------------------------------------*/

.jp-Cell {
  padding: var(--jp-cell-padding);
  margin: 0;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Common input/output
|----------------------------------------------------------------------------*/

.jp-Cell-inputWrapper,
.jp-Cell-outputWrapper {
  display: flex;
  flex-direction: row;
  padding: 0;
  margin: 0;

  /* Added to reveal the box-shadow on the input and output collapsers. */
  overflow: visible;
}

/* Only input/output areas inside cells */
.jp-Cell-inputArea,
.jp-Cell-outputArea {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Collapser
|----------------------------------------------------------------------------*/

/* Make the output collapser disappear when there is not output, but do so
 * in a manner that leaves it in the layout and preserves its width.
 */
.jp-Cell.jp-mod-noOutputs .jp-Cell-outputCollapser {
  border: none !important;
  background: transparent !important;
}

.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputCollapser {
  min-height: var(--jp-cell-collapser-min-height);
}

/*-----------------------------------------------------------------------------
| Output
|----------------------------------------------------------------------------*/

/* Put a space between input and output when there IS output */
.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputWrapper {
  margin-top: 5px;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea {
  overflow-y: auto;
  max-height: 24em;
  margin-left: var(--jp-private-cell-scrolling-output-offset);
  resize: vertical;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea[style*='height'] {
  max-height: unset;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea::after {
  content: ' ';
  box-shadow: inset 0 0 6px 2px rgb(0 0 0 / 30%);
  width: 100%;
  height: 100%;
  position: sticky;
  bottom: 0;
  top: 0;
  margin-top: -50%;
  float: left;
  display: block;
  pointer-events: none;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-child {
  padding-top: 6px;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-prompt {
  width: calc(
    var(--jp-cell-prompt-width) - var(--jp-private-cell-scrolling-output-offset)
  );
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-promptOverlay {
  left: calc(-1 * var(--jp-private-cell-scrolling-output-offset));
}

/*-----------------------------------------------------------------------------
| CodeCell
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| MarkdownCell
|----------------------------------------------------------------------------*/

.jp-MarkdownOutput {
  display: table-cell;
  width: 100%;
  margin-top: 0;
  margin-bottom: 0;
  padding-left: var(--jp-code-padding);
}

.jp-MarkdownOutput.jp-RenderedHTMLCommon {
  overflow: auto;
}

/* collapseHeadingButton (show always if hiddenCellsButton is _not_ shown) */
.jp-collapseHeadingButton {
  display: flex;
  min-height: var(--jp-cell-collapser-min-height);
  font-size: var(--jp-code-font-size);
  position: absolute;
  background-color: transparent;
  background-size: 25px;
  background-repeat: no-repeat;
  background-position-x: center;
  background-position-y: top;
  background-image: var(--jp-icon-caret-down);
  right: 0;
  top: 0;
  bottom: 0;
}

.jp-collapseHeadingButton.jp-mod-collapsed {
  background-image: var(--jp-icon-caret-right);
}

/*
 set the container font size to match that of content
 so that the nested collapse buttons have the right size
*/
.jp-MarkdownCell .jp-InputPrompt {
  font-size: var(--jp-content-font-size1);
}

/*
  Align collapseHeadingButton with cell top header
  The font sizes are identical to the ones in packages/rendermime/style/base.css
*/
.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='1'] {
  font-size: var(--jp-content-font-size5);
  background-position-y: calc(0.3 * var(--jp-content-font-size5));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='2'] {
  font-size: var(--jp-content-font-size4);
  background-position-y: calc(0.3 * var(--jp-content-font-size4));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='3'] {
  font-size: var(--jp-content-font-size3);
  background-position-y: calc(0.3 * var(--jp-content-font-size3));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='4'] {
  font-size: var(--jp-content-font-size2);
  background-position-y: calc(0.3 * var(--jp-content-font-size2));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='5'] {
  font-size: var(--jp-content-font-size1);
  background-position-y: top;
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='6'] {
  font-size: var(--jp-content-font-size0);
  background-position-y: top;
}

/* collapseHeadingButton (show only on (hover,active) if hiddenCellsButton is shown) */
.jp-Notebook.jp-mod-showHiddenCellsButton .jp-collapseHeadingButton {
  display: none;
}

.jp-Notebook.jp-mod-showHiddenCellsButton
  :is(.jp-MarkdownCell:hover, .jp-mod-active)
  .jp-collapseHeadingButton {
  display: flex;
}

/* showHiddenCellsButton (only show if jp-mod-showHiddenCellsButton is set, which
is a consequence of the showHiddenCellsButton option in Notebook Settings)*/
.jp-Notebook.jp-mod-showHiddenCellsButton .jp-showHiddenCellsButton {
  margin-left: calc(var(--jp-cell-prompt-width) + 2 * var(--jp-code-padding));
  margin-top: var(--jp-code-padding);
  border: 1px solid var(--jp-border-color2);
  background-color: var(--jp-border-color3) !important;
  color: var(--jp-content-font-color0) !important;
  display: flex;
}

.jp-Notebook.jp-mod-showHiddenCellsButton .jp-showHiddenCellsButton:hover {
  background-color: var(--jp-border-color2) !important;
}

.jp-showHiddenCellsButton {
  display: none;
}

/*-----------------------------------------------------------------------------
| Printing
|----------------------------------------------------------------------------*/

/*
Using block instead of flex to allow the use of the break-inside CSS property for
cell outputs.
*/

@media print {
  .jp-Cell-inputWrapper,
  .jp-Cell-outputWrapper {
    display: block;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-notebook-toolbar-padding: 2px 5px 2px 2px;
}

/*-----------------------------------------------------------------------------

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-NotebookPanel-toolbar {
  padding: var(--jp-notebook-toolbar-padding);

  /* disable paint containment from lumino 2.0 default strict CSS containment */
  contain: style size !important;
}

.jp-Toolbar-item.jp-Notebook-toolbarCellType .jp-select-wrapper.jp-mod-focused {
  border: none;
  box-shadow: none;
}

.jp-Notebook-toolbarCellTypeDropdown select {
  height: 24px;
  font-size: var(--jp-ui-font-size1);
  line-height: 14px;
  border-radius: 0;
  display: block;
}

.jp-Notebook-toolbarCellTypeDropdown span {
  top: 5px !important;
}

.jp-Toolbar-responsive-popup {
  position: absolute;
  height: fit-content;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: flex-end;
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  background: var(--jp-toolbar-background);
  min-height: var(--jp-toolbar-micro-height);
  padding: var(--jp-notebook-toolbar-padding);
  z-index: 1;
  right: 0;
  top: 0;
}

.jp-Toolbar > .jp-Toolbar-responsive-opener {
  margin-left: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-Notebook-ExecutionIndicator {
  position: relative;
  display: inline-block;
  height: 100%;
  z-index: 9997;
}

.jp-Notebook-ExecutionIndicator-tooltip {
  visibility: hidden;
  height: auto;
  width: max-content;
  width: -moz-max-content;
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color1);
  text-align: justify;
  border-radius: 6px;
  padding: 0 5px;
  position: fixed;
  display: table;
}

.jp-Notebook-ExecutionIndicator-tooltip.up {
  transform: translateX(-50%) translateY(-100%) translateY(-32px);
}

.jp-Notebook-ExecutionIndicator-tooltip.down {
  transform: translateX(calc(-100% + 16px)) translateY(5px);
}

.jp-Notebook-ExecutionIndicator-tooltip.hidden {
  display: none;
}

.jp-Notebook-ExecutionIndicator:hover .jp-Notebook-ExecutionIndicator-tooltip {
  visibility: visible;
}

.jp-Notebook-ExecutionIndicator span {
  font-size: var(--jp-ui-font-size1);
  font-family: var(--jp-ui-font-family);
  color: var(--jp-ui-font-color1);
  line-height: 24px;
  display: block;
}

.jp-Notebook-ExecutionIndicator-progress-bar {
  display: flex;
  justify-content: center;
  height: 100%;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*
 * Execution indicator
 */
.jp-tocItem-content::after {
  content: '';

  /* Must be identical to form a circle */
  width: 12px;
  height: 12px;
  background: none;
  border: none;
  position: absolute;
  right: 0;
}

.jp-tocItem-content[data-running='0']::after {
  border-radius: 50%;
  border: var(--jp-border-width) solid var(--jp-inverse-layout-color3);
  background: none;
}

.jp-tocItem-content[data-running='1']::after {
  border-radius: 50%;
  border: var(--jp-border-width) solid var(--jp-inverse-layout-color3);
  background-color: var(--jp-inverse-layout-color3);
}

.jp-tocItem-content[data-running='0'],
.jp-tocItem-content[data-running='1'] {
  margin-right: 12px;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-Notebook-footer {
  height: 27px;
  margin-left: calc(
    var(--jp-cell-prompt-width) + var(--jp-cell-collapser-width) +
      var(--jp-cell-padding)
  );
  width: calc(
    100% -
      (
        var(--jp-cell-prompt-width) + var(--jp-cell-collapser-width) +
          var(--jp-cell-padding) + var(--jp-cell-padding)
      )
  );
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  color: var(--jp-ui-font-color3);
  margin-top: 6px;
  background: none;
  cursor: pointer;
}

.jp-Notebook-footer:focus {
  border-color: var(--jp-cell-editor-active-border-color);
}

/* For devices that support hovering, hide footer until hover */
@media (hover: hover) {
  .jp-Notebook-footer {
    opacity: 0;
  }

  .jp-Notebook-footer:focus,
  .jp-Notebook-footer:hover {
    opacity: 1;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Imports
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-side-by-side-output-size: 1fr;
  --jp-side-by-side-resized-cell: var(--jp-side-by-side-output-size);
  --jp-private-notebook-dragImage-width: 304px;
  --jp-private-notebook-dragImage-height: 36px;
  --jp-private-notebook-selected-color: var(--md-blue-400);
  --jp-private-notebook-active-color: var(--md-green-400);
}

/*-----------------------------------------------------------------------------
| Notebook
|----------------------------------------------------------------------------*/

/* stylelint-disable selector-max-class */

.jp-NotebookPanel {
  display: block;
  height: 100%;
}

.jp-NotebookPanel.jp-Document {
  min-width: 240px;
  min-height: 120px;
}

.jp-Notebook {
  padding: var(--jp-notebook-padding);
  outline: none;
  overflow: auto;
  background: var(--jp-layout-color0);
}

.jp-Notebook.jp-mod-scrollPastEnd::after {
  display: block;
  content: '';
  min-height: var(--jp-notebook-scroll-padding);
}

.jp-MainAreaWidget-ContainStrict .jp-Notebook * {
  contain: strict;
}

.jp-Notebook .jp-Cell {
  overflow: visible;
}

.jp-Notebook .jp-Cell .jp-InputPrompt {
  cursor: move;
}

/*-----------------------------------------------------------------------------
| Notebook state related styling
|
| The notebook and cells each have states, here are the possibilities:
|
| - Notebook
|   - Command
|   - Edit
| - Cell
|   - None
|   - Active (only one can be active)
|   - Selected (the cells actions are applied to)
|   - Multiselected (when multiple selected, the cursor)
|   - No outputs
|----------------------------------------------------------------------------*/

/* Command or edit modes */

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-InputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-OutputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

/* cell is active */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser {
  background: var(--jp-brand-color1);
}

/* cell is dirty */
.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt {
  color: var(--jp-warn-color1);
}

.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt::before {
  color: var(--jp-warn-color1);
  content: '•';
}

.jp-Notebook .jp-Cell.jp-mod-active.jp-mod-dirty .jp-Collapser {
  background: var(--jp-warn-color1);
}

/* collapser is hovered */
.jp-Notebook .jp-Cell .jp-Collapser:hover {
  box-shadow: var(--jp-elevation-z2);
  background: var(--jp-brand-color1);
  opacity: var(--jp-cell-collapser-not-active-hover-opacity);
}

/* cell is active and collapser is hovered */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser:hover {
  background: var(--jp-brand-color0);
  opacity: 1;
}

/* Command mode */

.jp-Notebook.jp-mod-commandMode .jp-Cell.jp-mod-selected {
  background: var(--jp-notebook-multiselected-color);
}

.jp-Notebook.jp-mod-commandMode
  .jp-Cell.jp-mod-active.jp-mod-selected:not(.jp-mod-multiSelected) {
  background: transparent;
}

/* Edit mode */

.jp-Notebook.jp-mod-editMode .jp-Cell.jp-mod-active .jp-InputArea-editor {
  border: var(--jp-border-width) solid var(--jp-cell-editor-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-cell-editor-active-background);
}

/*-----------------------------------------------------------------------------
| Notebook drag and drop
|----------------------------------------------------------------------------*/

.jp-Notebook-cell.jp-mod-dropSource {
  opacity: 0.5;
}

.jp-Notebook-cell.jp-mod-dropTarget,
.jp-Notebook.jp-mod-commandMode
  .jp-Notebook-cell.jp-mod-active.jp-mod-selected.jp-mod-dropTarget {
  border-top-color: var(--jp-private-notebook-selected-color);
  border-top-style: solid;
  border-top-width: 2px;
}

.jp-dragImage {
  display: block;
  flex-direction: row;
  width: var(--jp-private-notebook-dragImage-width);
  height: var(--jp-private-notebook-dragImage-height);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background);
  overflow: visible;
}

.jp-dragImage-singlePrompt {
  box-shadow: 2px 2px 4px 0 rgba(0, 0, 0, 0.12);
}

.jp-dragImage .jp-dragImage-content {
  flex: 1 1 auto;
  z-index: 2;
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  line-height: var(--jp-code-line-height);
  padding: var(--jp-code-padding);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background-color);
  color: var(--jp-content-font-color3);
  text-align: left;
  margin: 4px 4px 4px 0;
}

.jp-dragImage .jp-dragImage-prompt {
  flex: 0 0 auto;
  min-width: 36px;
  color: var(--jp-cell-inprompt-font-color);
  padding: var(--jp-code-padding);
  padding-left: 12px;
  font-family: var(--jp-cell-prompt-font-family);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: 1.9;
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
}

.jp-dragImage-multipleBack {
  z-index: -1;
  position: absolute;
  height: 32px;
  width: 300px;
  top: 8px;
  left: 8px;
  background: var(--jp-layout-color2);
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  box-shadow: 2px 2px 4px 0 rgba(0, 0, 0, 0.12);
}

/*-----------------------------------------------------------------------------
| Cell toolbar
|----------------------------------------------------------------------------*/

.jp-NotebookTools {
  display: block;
  min-width: var(--jp-sidebar-min-width);
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);

  /* This is needed so that all font sizing of children done in ems is
    * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  overflow: auto;
}

.jp-ActiveCellTool {
  padding: 12px 0;
  display: flex;
}

.jp-ActiveCellTool-Content {
  flex: 1 1 auto;
}

.jp-ActiveCellTool .jp-ActiveCellTool-CellContent {
  background: var(--jp-cell-editor-background);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0;
  min-height: 29px;
}

.jp-ActiveCellTool .jp-InputPrompt {
  min-width: calc(var(--jp-cell-prompt-width) * 0.75);
}

.jp-ActiveCellTool-CellContent > pre {
  padding: 5px 4px;
  margin: 0;
  white-space: normal;
}

.jp-MetadataEditorTool {
  flex-direction: column;
  padding: 12px 0;
}

.jp-RankedPanel > :not(:first-child) {
  margin-top: 12px;
}

.jp-KeySelector select.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: var(--jp-border-width) solid var(--jp-border-color1);
}

.jp-KeySelector label,
.jp-MetadataEditorTool label,
.jp-NumberSetter label {
  line-height: 1.4;
}

.jp-NotebookTools .jp-select-wrapper {
  margin-top: 4px;
  margin-bottom: 0;
}

.jp-NumberSetter input {
  width: 100%;
  margin-top: 4px;
}

.jp-NotebookTools .jp-Collapse {
  margin-top: 16px;
}

/*-----------------------------------------------------------------------------
| Presentation Mode (.jp-mod-presentationMode)
|----------------------------------------------------------------------------*/

.jp-mod-presentationMode .jp-Notebook {
  --jp-content-font-size1: var(--jp-content-presentation-font-size1);
  --jp-code-font-size: var(--jp-code-presentation-font-size);
}

.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-InputPrompt,
.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-OutputPrompt {
  flex: 0 0 110px;
}

/*-----------------------------------------------------------------------------
| Side-by-side Mode (.jp-mod-sideBySide)
|----------------------------------------------------------------------------*/
.jp-mod-sideBySide.jp-Notebook .jp-Notebook-cell {
  margin-top: 3em;
  margin-bottom: 3em;
  margin-left: 5%;
  margin-right: 5%;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell {
  display: grid;
  grid-template-columns: minmax(0, 1fr) min-content minmax(
      0,
      var(--jp-side-by-side-output-size)
    );
  grid-template-rows: auto minmax(0, 1fr) auto;
  grid-template-areas:
    'header header header'
    'input handle output'
    'footer footer footer';
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell.jp-mod-resizedCell {
  grid-template-columns: minmax(0, 1fr) min-content minmax(
      0,
      var(--jp-side-by-side-resized-cell)
    );
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellHeader {
  grid-area: header;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-Cell-inputWrapper {
  grid-area: input;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-Cell-outputWrapper {
  /* overwrite the default margin (no vertical separation needed in side by side move */
  margin-top: 0;
  grid-area: output;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellFooter {
  grid-area: footer;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellResizeHandle {
  grid-area: handle;
  user-select: none;
  display: block;
  height: 100%;
  cursor: ew-resize;
  padding: 0 var(--jp-cell-padding);
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellResizeHandle::after {
  content: '';
  display: block;
  background: var(--jp-border-color2);
  height: 100%;
  width: 5px;
}

.jp-mod-sideBySide.jp-Notebook
  .jp-CodeCell.jp-mod-resizedCell
  .jp-CellResizeHandle::after {
  background: var(--jp-border-color0);
}

.jp-CellResizeHandle {
  display: none;
}

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Cell-Placeholder {
  padding-left: 55px;
}

.jp-Cell-Placeholder-wrapper {
  background: #fff;
  border: 1px solid;
  border-color: #e5e6e9 #dfe0e4 #d0d1d5;
  border-radius: 4px;
  -webkit-border-radius: 4px;
  margin: 10px 15px;
}

.jp-Cell-Placeholder-wrapper-inner {
  padding: 15px;
  position: relative;
}

.jp-Cell-Placeholder-wrapper-body {
  background-repeat: repeat;
  background-size: 50% auto;
}

.jp-Cell-Placeholder-wrapper-body div {
  background: #f6f7f8;
  background-image: -webkit-linear-gradient(
    left,
    #f6f7f8 0%,
    #edeef1 20%,
    #f6f7f8 40%,
    #f6f7f8 100%
  );
  background-repeat: no-repeat;
  background-size: 800px 104px;
  height: 104px;
  position: absolute;
  right: 15px;
  left: 15px;
  top: 15px;
}

div.jp-Cell-Placeholder-h1 {
  top: 20px;
  height: 20px;
  left: 15px;
  width: 150px;
}

div.jp-Cell-Placeholder-h2 {
  left: 15px;
  top: 50px;
  height: 10px;
  width: 100px;
}

div.jp-Cell-Placeholder-content-1,
div.jp-Cell-Placeholder-content-2,
div.jp-Cell-Placeholder-content-3 {
  left: 15px;
  right: 15px;
  height: 10px;
}

div.jp-Cell-Placeholder-content-1 {
  top: 100px;
}

div.jp-Cell-Placeholder-content-2 {
  top: 120px;
}

div.jp-Cell-Placeholder-content-3 {
  top: 140px;
}

</style>
<style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
The following CSS variables define the main, public API for styling JupyterLab.
These variables should be used by all plugins wherever possible. In other
words, plugins should not define custom colors, sizes, etc unless absolutely
necessary. This enables users to change the visual theme of JupyterLab
by changing these variables.

Many variables appear in an ordered sequence (0,1,2,3). These sequences
are designed to work well together, so for example, `--jp-border-color1` should
be used with `--jp-layout-color1`. The numbers have the following meanings:

* 0: super-primary, reserved for special emphasis
* 1: primary, most important under normal situations
* 2: secondary, next most important under normal situations
* 3: tertiary, next most important under normal situations

Throughout JupyterLab, we are mostly following principles from Google's
Material Design when selecting colors. We are not, however, following
all of MD as it is not optimized for dense, information rich UIs.
*/

:root {
  /* Elevation
   *
   * We style box-shadows using Material Design's idea of elevation. These particular numbers are taken from here:
   *
   * https://github.com/material-components/material-components-web
   * https://material-components-web.appspot.com/elevation.html
   */

  --jp-shadow-base-lightness: 0;
  --jp-shadow-umbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.2
  );
  --jp-shadow-penumbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.14
  );
  --jp-shadow-ambient-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.12
  );
  --jp-elevation-z0: none;
  --jp-elevation-z1: 0 2px 1px -1px var(--jp-shadow-umbra-color),
    0 1px 1px 0 var(--jp-shadow-penumbra-color),
    0 1px 3px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z2: 0 3px 1px -2px var(--jp-shadow-umbra-color),
    0 2px 2px 0 var(--jp-shadow-penumbra-color),
    0 1px 5px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z4: 0 2px 4px -1px var(--jp-shadow-umbra-color),
    0 4px 5px 0 var(--jp-shadow-penumbra-color),
    0 1px 10px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z6: 0 3px 5px -1px var(--jp-shadow-umbra-color),
    0 6px 10px 0 var(--jp-shadow-penumbra-color),
    0 1px 18px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z8: 0 5px 5px -3px var(--jp-shadow-umbra-color),
    0 8px 10px 1px var(--jp-shadow-penumbra-color),
    0 3px 14px 2px var(--jp-shadow-ambient-color);
  --jp-elevation-z12: 0 7px 8px -4px var(--jp-shadow-umbra-color),
    0 12px 17px 2px var(--jp-shadow-penumbra-color),
    0 5px 22px 4px var(--jp-shadow-ambient-color);
  --jp-elevation-z16: 0 8px 10px -5px var(--jp-shadow-umbra-color),
    0 16px 24px 2px var(--jp-shadow-penumbra-color),
    0 6px 30px 5px var(--jp-shadow-ambient-color);
  --jp-elevation-z20: 0 10px 13px -6px var(--jp-shadow-umbra-color),
    0 20px 31px 3px var(--jp-shadow-penumbra-color),
    0 8px 38px 7px var(--jp-shadow-ambient-color);
  --jp-elevation-z24: 0 11px 15px -7px var(--jp-shadow-umbra-color),
    0 24px 38px 3px var(--jp-shadow-penumbra-color),
    0 9px 46px 8px var(--jp-shadow-ambient-color);

  /* Borders
   *
   * The following variables, specify the visual styling of borders in JupyterLab.
   */

  --jp-border-width: 1px;
  --jp-border-color0: var(--md-grey-400);
  --jp-border-color1: var(--md-grey-400);
  --jp-border-color2: var(--md-grey-300);
  --jp-border-color3: var(--md-grey-200);
  --jp-inverse-border-color: var(--md-grey-600);
  --jp-border-radius: 2px;

  /* UI Fonts
   *
   * The UI font CSS variables are used for the typography all of the JupyterLab
   * user interface elements that are not directly user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-ui-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-ui-font-scale-factor: 1.2;
  --jp-ui-font-size0: 0.83333em;
  --jp-ui-font-size1: 13px; /* Base font size */
  --jp-ui-font-size2: 1.2em;
  --jp-ui-font-size3: 1.44em;
  --jp-ui-font-family: system-ui, -apple-system, blinkmacsystemfont, 'Segoe UI',
    helvetica, arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji',
    'Segoe UI Symbol';

  /*
   * Use these font colors against the corresponding main layout colors.
   * In a light theme, these go from dark to light.
   */

  /* Defaults use Material Design specification */
  --jp-ui-font-color0: rgba(0, 0, 0, 1);
  --jp-ui-font-color1: rgba(0, 0, 0, 0.87);
  --jp-ui-font-color2: rgba(0, 0, 0, 0.54);
  --jp-ui-font-color3: rgba(0, 0, 0, 0.38);

  /*
   * Use these against the brand/accent/warn/error colors.
   * These will typically go from light to darker, in both a dark and light theme.
   */

  --jp-ui-inverse-font-color0: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color1: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color2: rgba(255, 255, 255, 0.7);
  --jp-ui-inverse-font-color3: rgba(255, 255, 255, 0.5);

  /* Content Fonts
   *
   * Content font variables are used for typography of user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-content-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-content-line-height: 1.6;
  --jp-content-font-scale-factor: 1.2;
  --jp-content-font-size0: 0.83333em;
  --jp-content-font-size1: 14px; /* Base font size */
  --jp-content-font-size2: 1.2em;
  --jp-content-font-size3: 1.44em;
  --jp-content-font-size4: 1.728em;
  --jp-content-font-size5: 2.0736em;

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-content-presentation-font-size1: 17px;
  --jp-content-heading-line-height: 1;
  --jp-content-heading-margin-top: 1.2em;
  --jp-content-heading-margin-bottom: 0.8em;
  --jp-content-heading-font-weight: 500;

  /* Defaults use Material Design specification */
  --jp-content-font-color0: rgba(0, 0, 0, 1);
  --jp-content-font-color1: rgba(0, 0, 0, 0.87);
  --jp-content-font-color2: rgba(0, 0, 0, 0.54);
  --jp-content-font-color3: rgba(0, 0, 0, 0.38);
  --jp-content-link-color: var(--md-blue-900);
  --jp-content-font-family: system-ui, -apple-system, blinkmacsystemfont,
    'Segoe UI', helvetica, arial, sans-serif, 'Apple Color Emoji',
    'Segoe UI Emoji', 'Segoe UI Symbol';

  /*
   * Code Fonts
   *
   * Code font variables are used for typography of code and other monospaces content.
   */

  --jp-code-font-size: 13px;
  --jp-code-line-height: 1.3077; /* 17px for 13px base */
  --jp-code-padding: 5px; /* 5px for 13px base, codemirror highlighting needs integer px value */
  --jp-code-font-family-default: menlo, consolas, 'DejaVu Sans Mono', monospace;
  --jp-code-font-family: var(--jp-code-font-family-default);

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-code-presentation-font-size: 16px;

  /* may need to tweak cursor width if you change font size */
  --jp-code-cursor-width0: 1.4px;
  --jp-code-cursor-width1: 2px;
  --jp-code-cursor-width2: 4px;

  /* Layout
   *
   * The following are the main layout colors use in JupyterLab. In a light
   * theme these would go from light to dark.
   */

  --jp-layout-color0: white;
  --jp-layout-color1: white;
  --jp-layout-color2: var(--md-grey-200);
  --jp-layout-color3: var(--md-grey-400);
  --jp-layout-color4: var(--md-grey-600);

  /* Inverse Layout
   *
   * The following are the inverse layout colors use in JupyterLab. In a light
   * theme these would go from dark to light.
   */

  --jp-inverse-layout-color0: #111;
  --jp-inverse-layout-color1: var(--md-grey-900);
  --jp-inverse-layout-color2: var(--md-grey-800);
  --jp-inverse-layout-color3: var(--md-grey-700);
  --jp-inverse-layout-color4: var(--md-grey-600);

  /* Brand/accent */

  --jp-brand-color0: var(--md-blue-900);
  --jp-brand-color1: var(--md-blue-700);
  --jp-brand-color2: var(--md-blue-300);
  --jp-brand-color3: var(--md-blue-100);
  --jp-brand-color4: var(--md-blue-50);
  --jp-accent-color0: var(--md-green-900);
  --jp-accent-color1: var(--md-green-700);
  --jp-accent-color2: var(--md-green-300);
  --jp-accent-color3: var(--md-green-100);

  /* State colors (warn, error, success, info) */

  --jp-warn-color0: var(--md-orange-900);
  --jp-warn-color1: var(--md-orange-700);
  --jp-warn-color2: var(--md-orange-300);
  --jp-warn-color3: var(--md-orange-100);
  --jp-error-color0: var(--md-red-900);
  --jp-error-color1: var(--md-red-700);
  --jp-error-color2: var(--md-red-300);
  --jp-error-color3: var(--md-red-100);
  --jp-success-color0: var(--md-green-900);
  --jp-success-color1: var(--md-green-700);
  --jp-success-color2: var(--md-green-300);
  --jp-success-color3: var(--md-green-100);
  --jp-info-color0: var(--md-cyan-900);
  --jp-info-color1: var(--md-cyan-700);
  --jp-info-color2: var(--md-cyan-300);
  --jp-info-color3: var(--md-cyan-100);

  /* Cell specific styles */

  --jp-cell-padding: 5px;
  --jp-cell-collapser-width: 8px;
  --jp-cell-collapser-min-height: 20px;
  --jp-cell-collapser-not-active-hover-opacity: 0.6;
  --jp-cell-editor-background: var(--md-grey-100);
  --jp-cell-editor-border-color: var(--md-grey-300);
  --jp-cell-editor-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-cell-editor-active-background: var(--jp-layout-color0);
  --jp-cell-editor-active-border-color: var(--jp-brand-color1);
  --jp-cell-prompt-width: 64px;
  --jp-cell-prompt-font-family: var(--jp-code-font-family-default);
  --jp-cell-prompt-letter-spacing: 0;
  --jp-cell-prompt-opacity: 1;
  --jp-cell-prompt-not-active-opacity: 0.5;
  --jp-cell-prompt-not-active-font-color: var(--md-grey-700);

  /* A custom blend of MD grey and blue 600
   * See https://meyerweb.com/eric/tools/color-blend/#546E7A:1E88E5:5:hex */
  --jp-cell-inprompt-font-color: #307fc1;

  /* A custom blend of MD grey and orange 600
   * https://meyerweb.com/eric/tools/color-blend/#546E7A:F4511E:5:hex */
  --jp-cell-outprompt-font-color: #bf5b3d;

  /* Notebook specific styles */

  --jp-notebook-padding: 10px;
  --jp-notebook-select-background: var(--jp-layout-color1);
  --jp-notebook-multiselected-color: var(--md-blue-50);

  /* The scroll padding is calculated to fill enough space at the bottom of the
  notebook to show one single-line cell (with appropriate padding) at the top
  when the notebook is scrolled all the way to the bottom. We also subtract one
  pixel so that no scrollbar appears if we have just one single-line cell in the
  notebook. This padding is to enable a 'scroll past end' feature in a notebook.
  */
  --jp-notebook-scroll-padding: calc(
    100% - var(--jp-code-font-size) * var(--jp-code-line-height) -
      var(--jp-code-padding) - var(--jp-cell-padding) - 1px
  );

  /* Rendermime styles */

  --jp-rendermime-error-background: #fdd;
  --jp-rendermime-table-row-background: var(--md-grey-100);
  --jp-rendermime-table-row-hover-background: var(--md-light-blue-50);

  /* Dialog specific styles */

  --jp-dialog-background: rgba(0, 0, 0, 0.25);

  /* Console specific styles */

  --jp-console-padding: 10px;

  /* Toolbar specific styles */

  --jp-toolbar-border-color: var(--jp-border-color1);
  --jp-toolbar-micro-height: 8px;
  --jp-toolbar-background: var(--jp-layout-color1);
  --jp-toolbar-box-shadow: 0 0 2px 0 rgba(0, 0, 0, 0.24);
  --jp-toolbar-header-margin: 4px 4px 0 4px;
  --jp-toolbar-active-background: var(--md-grey-300);

  /* Statusbar specific styles */

  --jp-statusbar-height: 24px;

  /* Input field styles */

  --jp-input-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-input-active-background: var(--jp-layout-color1);
  --jp-input-hover-background: var(--jp-layout-color1);
  --jp-input-background: var(--md-grey-100);
  --jp-input-border-color: var(--jp-inverse-border-color);
  --jp-input-active-border-color: var(--jp-brand-color1);
  --jp-input-active-box-shadow-color: rgba(19, 124, 189, 0.3);

  /* General editor styles */

  --jp-editor-selected-background: #d9d9d9;
  --jp-editor-selected-focused-background: #d7d4f0;
  --jp-editor-cursor-color: var(--jp-ui-font-color0);

  /* Code mirror specific styles */

  --jp-mirror-editor-keyword-color: #008000;
  --jp-mirror-editor-atom-color: #88f;
  --jp-mirror-editor-number-color: #080;
  --jp-mirror-editor-def-color: #00f;
  --jp-mirror-editor-variable-color: var(--md-grey-900);
  --jp-mirror-editor-variable-2-color: rgb(0, 54, 109);
  --jp-mirror-editor-variable-3-color: #085;
  --jp-mirror-editor-punctuation-color: #05a;
  --jp-mirror-editor-property-color: #05a;
  --jp-mirror-editor-operator-color: #a2f;
  --jp-mirror-editor-comment-color: #408080;
  --jp-mirror-editor-string-color: #ba2121;
  --jp-mirror-editor-string-2-color: #708;
  --jp-mirror-editor-meta-color: #a2f;
  --jp-mirror-editor-qualifier-color: #555;
  --jp-mirror-editor-builtin-color: #008000;
  --jp-mirror-editor-bracket-color: #997;
  --jp-mirror-editor-tag-color: #170;
  --jp-mirror-editor-attribute-color: #00c;
  --jp-mirror-editor-header-color: blue;
  --jp-mirror-editor-quote-color: #090;
  --jp-mirror-editor-link-color: #00c;
  --jp-mirror-editor-error-color: #f00;
  --jp-mirror-editor-hr-color: #999;

  /*
    RTC user specific colors.
    These colors are used for the cursor, username in the editor,
    and the icon of the user.
  */

  --jp-collaborator-color1: #ffad8e;
  --jp-collaborator-color2: #dac83d;
  --jp-collaborator-color3: #72dd76;
  --jp-collaborator-color4: #00e4d0;
  --jp-collaborator-color5: #45d4ff;
  --jp-collaborator-color6: #e2b1ff;
  --jp-collaborator-color7: #ff9de6;

  /* Vega extension styles */

  --jp-vega-background: white;

  /* Sidebar-related styles */

  --jp-sidebar-min-width: 250px;

  /* Search-related styles */

  --jp-search-toggle-off-opacity: 0.5;
  --jp-search-toggle-hover-opacity: 0.8;
  --jp-search-toggle-on-opacity: 1;
  --jp-search-selected-match-background-color: rgb(245, 200, 0);
  --jp-search-selected-match-color: black;
  --jp-search-unselected-match-background-color: var(
    --jp-inverse-layout-color0
  );
  --jp-search-unselected-match-color: var(--jp-ui-inverse-font-color0);

  /* Icon colors that work well with light or dark backgrounds */
  --jp-icon-contrast-color0: var(--md-purple-600);
  --jp-icon-contrast-color1: var(--md-green-600);
  --jp-icon-contrast-color2: var(--md-pink-600);
  --jp-icon-contrast-color3: var(--md-blue-600);

  /* Button colors */
  --jp-accept-color-normal: var(--md-blue-700);
  --jp-accept-color-hover: var(--md-blue-800);
  --jp-accept-color-active: var(--md-blue-900);
  --jp-warn-color-normal: var(--md-red-700);
  --jp-warn-color-hover: var(--md-red-800);
  --jp-warn-color-active: var(--md-red-900);
  --jp-reject-color-normal: var(--md-grey-600);
  --jp-reject-color-hover: var(--md-grey-700);
  --jp-reject-color-active: var(--md-grey-800);

  /* File or activity icons and switch semantic variables */
  --jp-jupyter-icon-color: #f37626;
  --jp-notebook-icon-color: #f37626;
  --jp-json-icon-color: var(--md-orange-700);
  --jp-console-icon-background-color: var(--md-blue-700);
  --jp-console-icon-color: white;
  --jp-terminal-icon-background-color: var(--md-grey-800);
  --jp-terminal-icon-color: var(--md-grey-200);
  --jp-text-editor-icon-color: var(--md-grey-700);
  --jp-inspector-icon-color: var(--md-grey-700);
  --jp-switch-color: var(--md-grey-400);
  --jp-switch-true-position-color: var(--md-orange-900);
}
</style>
<style type="text/css">
/* Force rendering true colors when outputing to pdf */
* {
  -webkit-print-color-adjust: exact;
}

/* Misc */
a.anchor-link {
  display: none;
}

/* Input area styling */
.jp-InputArea {
  overflow: hidden;
}

.jp-InputArea-editor {
  overflow: hidden;
}

.cm-editor.cm-s-jupyter .highlight pre {
/* weird, but --jp-code-padding defined to be 5px but 4px horizontal padding is hardcoded for pre.cm-line */
  padding: var(--jp-code-padding) 4px;
  margin: 0;

  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
  color: inherit;

}

.jp-OutputArea-output pre {
  line-height: inherit;
  font-family: inherit;
}

.jp-RenderedText pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
}

/* Hiding the collapser by default */
.jp-Collapser {
  display: none;
}

@page {
    margin: 0.5in; /* Margin for each printed piece of paper */
}

@media print {
  .jp-Cell-inputWrapper,
  .jp-Cell-outputWrapper {
    display: block;
  }
}
</style>
<!-- Load mathjax -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/latest.js?config=TeX-AMS_CHTML-full,Safe"> </script>
<!-- MathJax configuration -->
<script type="text/x-mathjax-config">
    init_mathjax = function() {
        if (window.MathJax) {
        // MathJax loaded
            MathJax.Hub.Config({
                TeX: {
                    equationNumbers: {
                    autoNumber: "AMS",
                    useLabelIds: true
                    }
                },
                tex2jax: {
                    inlineMath: [ ['$','$'], ["\\(","\\)"] ],
                    displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
                    processEscapes: true,
                    processEnvironments: true
                },
                displayAlign: 'center',
                messageStyle: 'none',
                CommonHTML: {
                    linebreaks: {
                    automatic: true
                    }
                }
            });

            MathJax.Hub.Queue(["Typeset", MathJax.Hub]);
        }
    }
    init_mathjax();
    </script>
<!-- End of mathjax configuration --><script type="module">
  document.addEventListener("DOMContentLoaded", async () => {
    const diagrams = document.querySelectorAll(".jp-Mermaid > pre.mermaid");
    // do not load mermaidjs if not needed
    if (!diagrams.length) {
      return;
    }
    const mermaid = (await import("https://cdnjs.cloudflare.com/ajax/libs/mermaid/10.7.0/mermaid.esm.min.mjs")).default;
    const parser = new DOMParser();

    mermaid.initialize({
      maxTextSize: 100000,
      maxEdges: 100000,
      startOnLoad: false,
      fontFamily: window
        .getComputedStyle(document.body)
        .getPropertyValue("--jp-ui-font-family"),
      theme: document.querySelector("body[data-jp-theme-light='true']")
        ? "default"
        : "dark",
    });

    let _nextMermaidId = 0;

    function makeMermaidImage(svg) {
      const img = document.createElement("img");
      const doc = parser.parseFromString(svg, "image/svg+xml");
      const svgEl = doc.querySelector("svg");
      const { maxWidth } = svgEl?.style || {};
      const firstTitle = doc.querySelector("title");
      const firstDesc = doc.querySelector("desc");

      img.setAttribute("src", `data:image/svg+xml,${encodeURIComponent(svg)}`);
      if (maxWidth) {
        img.width = parseInt(maxWidth);
      }
      if (firstTitle) {
        img.setAttribute("alt", firstTitle.textContent);
      }
      if (firstDesc) {
        const caption = document.createElement("figcaption");
        caption.className = "sr-only";
        caption.textContent = firstDesc.textContent;
        return [img, caption];
      }
      return [img];
    }

    async function makeMermaidError(text) {
      let errorMessage = "";
      try {
        await mermaid.parse(text);
      } catch (err) {
        errorMessage = `${err}`;
      }

      const result = document.createElement("details");
      result.className = 'jp-RenderedMermaid-Details';
      const summary = document.createElement("summary");
      summary.className = 'jp-RenderedMermaid-Summary';
      const pre = document.createElement("pre");
      const code = document.createElement("code");
      code.innerText = text;
      pre.appendChild(code);
      summary.appendChild(pre);
      result.appendChild(summary);

      const warning = document.createElement("pre");
      warning.innerText = errorMessage;
      result.appendChild(warning);
      return [result];
    }

    async function renderOneMarmaid(src) {
      const id = `jp-mermaid-${_nextMermaidId++}`;
      const parent = src.parentNode;
      let raw = src.textContent.trim();
      const el = document.createElement("div");
      el.style.visibility = "hidden";
      document.body.appendChild(el);
      let results = null;
      let output = null;
      try {
        let { svg } = await mermaid.render(id, raw, el);
        svg = cleanMermaidSvg(svg);
        results = makeMermaidImage(svg);
        output = document.createElement("figure");
        results.map(output.appendChild, output);
      } catch (err) {
        parent.classList.add("jp-mod-warning");
        results = await makeMermaidError(raw);
        output = results[0];
      } finally {
        el.remove();
      }
      parent.classList.add("jp-RenderedMermaid");
      parent.appendChild(output);
    }


    /**
     * Post-process to ensure mermaid diagrams contain only valid SVG and XHTML.
     */
    function cleanMermaidSvg(svg) {
      return svg.replace(RE_VOID_ELEMENT, replaceVoidElement);
    }


    /**
     * A regular expression for all void elements, which may include attributes and
     * a slash.
     *
     * @see https://developer.mozilla.org/en-US/docs/Glossary/Void_element
     *
     * Of these, only `<br>` is generated by Mermaid in place of `\n`,
     * but _any_ "malformed" tag will break the SVG rendering entirely.
     */
    const RE_VOID_ELEMENT =
      /<\s*(area|base|br|col|embed|hr|img|input|link|meta|param|source|track|wbr)\s*([^>]*?)\s*>/gi;

    /**
     * Ensure a void element is closed with a slash, preserving any attributes.
     */
    function replaceVoidElement(match, tag, rest) {
      rest = rest.trim();
      if (!rest.endsWith('/')) {
        rest = `${rest} /`;
      }
      return `<${tag} ${rest}>`;
    }

    void Promise.all([...diagrams].map(renderOneMarmaid));
  });
</script>
<style>
  .jp-Mermaid:not(.jp-RenderedMermaid) {
    display: none;
  }

  .jp-RenderedMermaid {
    overflow: auto;
    display: flex;
  }

  .jp-RenderedMermaid.jp-mod-warning {
    width: auto;
    padding: 0.5em;
    margin-top: 0.5em;
    border: var(--jp-border-width) solid var(--jp-warn-color2);
    border-radius: var(--jp-border-radius);
    color: var(--jp-ui-font-color1);
    font-size: var(--jp-ui-font-size1);
    white-space: pre-wrap;
    word-wrap: break-word;
  }

  .jp-RenderedMermaid figure {
    margin: 0;
    overflow: auto;
    max-width: 100%;
  }

  .jp-RenderedMermaid img {
    max-width: 100%;
  }

  .jp-RenderedMermaid-Details > pre {
    margin-top: 1em;
  }

  .jp-RenderedMermaid-Summary {
    color: var(--jp-warn-color2);
  }

  .jp-RenderedMermaid:not(.jp-mod-warning) pre {
    display: none;
  }

  .jp-RenderedMermaid-Summary > pre {
    display: inline-block;
    white-space: normal;
  }
</style>
<!-- End of mermaid configuration --></head>
<body class="jp-Notebook" data-jp-theme-light="true" data-jp-theme-name="JupyterLab Light">
<main>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell" id="cell-id=6bc6625a">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h1 id="Loan-payback">Loan payback<a class="anchor-link" href="#Loan-payback">¶</a></h1>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell" id="cell-id=cf4759f6">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [2]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="c1"># set up</span>
<span class="kn">import</span><span class="w"> </span><span class="nn">pandas</span><span class="w"> </span><span class="k">as</span><span class="w"> </span><span class="nn">pd</span>
<span class="kn">import</span><span class="w"> </span><span class="nn">matplotlib.pyplot</span><span class="w"> </span><span class="k">as</span><span class="w"> </span><span class="nn">plt</span>
<span class="kn">import</span><span class="w"> </span><span class="nn">numpy</span><span class="w"> </span><span class="k">as</span><span class="w"> </span><span class="nn">np</span>
<span class="kn">import</span><span class="w"> </span><span class="nn">matplotlib.ticker</span><span class="w"> </span><span class="k">as</span><span class="w"> </span><span class="nn">mtick</span>
<span class="kn">from</span><span class="w"> </span><span class="nn">matplotlib.ticker</span><span class="w"> </span><span class="kn">import</span> <span class="n">PercentFormatter</span>
<span class="kn">from</span><span class="w"> </span><span class="nn">sklearn.datasets</span><span class="w"> </span><span class="kn">import</span> <span class="n">load_iris</span>

<span class="c1"># Example: Load the Iris dataset</span>
<span class="n">iris</span> <span class="o">=</span> <span class="n">load_iris</span><span class="p">()</span>
<span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">iris</span><span class="o">.</span><span class="n">data</span><span class="p">)</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">10</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[2]:</div>
<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html" tabindex="0">
<div>
<style scoped="">
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
<thead>
<tr style="text-align: right;">
<th></th>
<th>0</th>
<th>1</th>
<th>2</th>
<th>3</th>
</tr>
</thead>
<tbody>
<tr>
<th>0</th>
<td>5.1</td>
<td>3.5</td>
<td>1.4</td>
<td>0.2</td>
</tr>
<tr>
<th>1</th>
<td>4.9</td>
<td>3.0</td>
<td>1.4</td>
<td>0.2</td>
</tr>
<tr>
<th>2</th>
<td>4.7</td>
<td>3.2</td>
<td>1.3</td>
<td>0.2</td>
</tr>
<tr>
<th>3</th>
<td>4.6</td>
<td>3.1</td>
<td>1.5</td>
<td>0.2</td>
</tr>
<tr>
<th>4</th>
<td>5.0</td>
<td>3.6</td>
<td>1.4</td>
<td>0.2</td>
</tr>
<tr>
<th>5</th>
<td>5.4</td>
<td>3.9</td>
<td>1.7</td>
<td>0.4</td>
</tr>
<tr>
<th>6</th>
<td>4.6</td>
<td>3.4</td>
<td>1.4</td>
<td>0.3</td>
</tr>
<tr>
<th>7</th>
<td>5.0</td>
<td>3.4</td>
<td>1.5</td>
<td>0.2</td>
</tr>
<tr>
<th>8</th>
<td>4.4</td>
<td>2.9</td>
<td>1.4</td>
<td>0.2</td>
</tr>
<tr>
<th>9</th>
<td>4.9</td>
<td>3.1</td>
<td>1.5</td>
<td>0.1</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell" id="cell-id=94ef7426">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [4]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-ipython3"><pre><span></span><span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">iris</span><span class="o">.</span><span class="n">data</span><span class="p">)</span><span class="o">.</span><span class="n">plot</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[4]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>&lt;Axes: &gt;</pre>
</div>
</div>
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedImage jp-OutputArea-output" tabindex="0">
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,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"/>
</div>
</div>
</div>
</div>
</div>
</main>
</body>
</html>

Back to [main page](https://znogbes.github.io/python-portfolio/)