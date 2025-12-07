# VS Code Theme Color Properties Legend

This legend lists every VS Code theme color property variable, grouped by category, with descriptions of what each property affects. Properties are defined in the `workbench.colorCustomizations` setting.

## Color Formats
Color values support hexadecimal notations: `#RGB`, `#RGBA`, `#RRGGBB`, `#RRGGBBAA`. Alpha defaults to `ff` (opaque) if not specified. Some colors should not be opaque to avoid covering annotations.

## Contrast Colors
- `contrastActiveBorder`: Extra border around active elements for greater contrast.
- `contrastBorder`: Extra border around elements for greater contrast.

## Base Colors
- `focusBorder`: Overall border color for focused elements.
- `foreground`: Overall foreground color.
- `disabledForeground`: Overall foreground for disabled elements.
- `widget.border`: Border color of widgets like Find/Replace.
- `widget.shadow`: Shadow color of widgets like Find/Replace.
- `selection.background`: Background color of text selections in the workbench.
- `descriptionForeground`: Foreground color for description text.
- `errorForeground`: Overall foreground color for error messages.
- `icon.foreground`: Default color for icons.
- `sash.hoverBorder`: Hover border color for draggable sashes.

## Window Border
- `window.activeBorder`: Border color for the active window.
- `window.inactiveBorder`: Border color for inactive windows.

## Text Colors
- `textBlockQuote.background`: Background color for block quotes.
- `textBlockQuote.border`: Border color for block quotes.
- `textCodeBlock.background`: Background color for code blocks.
- `textLink.activeForeground`: Foreground color for clicked links.
- `textLink.foreground`: Foreground color for links.
- `textPreformat.foreground`: Foreground color for preformatted text.
- `textPreformat.background`: Background color for preformatted text.
- `textSeparator.foreground`: Color for text separators.

## Action Colors
- `toolbar.hoverBackground`: Toolbar background when hovering over actions.
- `toolbar.hoverOutline`: Toolbar outline when hovering over actions.
- `toolbar.activeBackground`: Toolbar background when holding mouse over actions.
- `editorActionList.background`: Action List background color.
- `editorActionList.foreground`: Action List foreground color.
- `editorActionList.focusForeground`: Action List foreground for focused item.
- `editorActionList.focusBackground`: Action List background for focused item.

## Button Control
- `button.background`: Button background color.
- `button.foreground`: Button foreground color.
- `button.border`: Button border color.
- `button.separator`: Button separator color.
- `button.hoverBackground`: Button background when hovering.
- `button.secondaryForeground`: Secondary button foreground color.
- `button.secondaryBackground`: Secondary button background color.
- `button.secondaryHoverBackground`: Secondary button background when hovering.
- `checkbox.background`: Background color of checkbox.
- `checkbox.foreground`: Foreground color of checkbox.
- `checkbox.disabled.background`: Background of disabled checkbox.
- `checkbox.disabled.foreground`: Foreground of disabled checkbox.
- `checkbox.border`: Border color of checkbox.
- `checkbox.selectBackground`: Background color of checkbox when selected.
- `checkbox.selectBorder`: Border color of checkbox when selected.
- `radio.activeForeground`: Foreground color of active radio option.
- `radio.activeBackground`: Background color of active radio option.
- `radio.activeBorder`: Border color of active radio option.
- `radio.inactiveForeground`: Foreground color of inactive radio option.
- `radio.inactiveBackground`: Background color of inactive radio option.
- `radio.inactiveBorder`: Border color of inactive radio option.
- `radio.inactiveHoverBackground`: Background color of inactive radio option when hovering.

## Dropdown Control
- `dropdown.background`: Dropdown background.
- `dropdown.listBackground`: Dropdown list background.
- `dropdown.border`: Dropdown border.
- `dropdown.foreground`: Dropdown foreground.

## Input Control
- `input.background`: Input box background.
- `input.border`: Input box border.
- `input.foreground`: Input box foreground.
- `input.placeholderForeground`: Input box foreground for placeholder text.
- `inputOption.activeBackground`: Background color of activated options in input fields.
- `inputOption.activeBorder`: Border color of activated options in input fields.
- `inputOption.activeForeground`: Foreground color of activated options in input fields.
- `inputOption.hoverBackground`: Background color of activated options in input fields.
- `inputValidation.errorBackground`: Input validation background for error severity.
- `inputValidation.errorForeground`: Input validation foreground for error severity.
- `inputValidation.errorBorder`: Input validation border for error severity.
- `inputValidation.infoBackground`: Input validation background for information severity.
- `inputValidation.infoForeground`: Input validation foreground for information severity.
- `inputValidation.infoBorder`: Input validation border for information severity.
- `inputValidation.warningBackground`: Input validation background for warning severity.
- `inputValidation.warningForeground`: Input validation foreground for warning severity.
- `inputValidation.warningBorder`: Input validation border for warning severity.

## Scrollbar Control
- `scrollbar.background`: Scrollbar track background color.
- `scrollbar.shadow`: Scrollbar slider shadow.
- `scrollbarSlider.activeBackground`: Scrollbar slider background when clicked.
- `scrollbarSlider.background`: Scrollbar slider background color.
- `scrollbarSlider.hoverBackground`: Scrollbar slider background when hovering.

## Badge
- `badge.foreground`: Badge foreground color.
- `badge.background`: Badge background color.

## Progress Bar
- `progressBar.background`: Background color of progress bar.

## Lists and Trees
- `list.activeSelectionBackground`: Background color for selected item when active.
- `list.activeSelectionForeground`: Foreground color for selected item when active.
- `list.activeSelectionIconForeground`: Icon foreground for selected item when active.
- `list.dropBackground`: Drag and drop background.
- `list.focusBackground`: Background color for focused item when active.
- `list.focusForeground`: Foreground color for focused item when active.
- `list.focusHighlightForeground`: Foreground of match highlights on focused items.
- `list.focusOutline`: Outline color for focused item when active.
- `list.focusAndSelectionOutline`: Outline color for focused and selected item.
- `list.highlightForeground`: Foreground of match highlights.
- `list.hoverBackground`: Background when hovering over items.
- `list.hoverForeground`: Foreground when hovering over items.
- `list.inactiveSelectionBackground`: Background color for selected item when inactive.
- `list.inactiveSelectionForeground`: Foreground color for selected item when inactive.
- `list.inactiveSelectionIconForeground`: Icon foreground for selected item when inactive.
- `list.inactiveFocusBackground`: Background color for focused item when inactive.
- `list.inactiveFocusOutline`: Outline color for focused item when inactive.
- `list.invalidItemForeground`: Foreground color for invalid items.
- `list.errorForeground`: Foreground color of list items with errors.
- `list.warningForeground`: Foreground color of list items with warnings.
- `listFilterWidget.background`: Background color of typed text in filter.
- `listFilterWidget.outline`: Outline color of typed text in filter.
- `listFilterWidget.noMatchesOutline`: Outline color when no match found.
- `listFilterWidget.shadow`: Shadow color of filter widget.
- `list.filterMatchBackground`: Background color of filtered matches.
- `list.filterMatchBorder`: Border color of filtered matches.
- `list.deemphasizedForeground`: Foreground color for deemphasized items.
- `list.dropBetweenBackground`: Drag and drop border between items.
- `tree.indentGuidesStroke`: Stroke color for indent guides.
- `tree.inactiveIndentGuidesStroke`: Stroke color for inactive indent guides.
- `tree.tableColumnsBorder`: Stroke color for table columns.
- `tree.tableOddRowsBackground`: Background color for odd table rows.

## Activity Bar
- `activityBar.background`: Activity Bar background color.
- `activityBar.dropBorder`: Drag and drop feedback color.
- `activityBar.foreground`: Activity Bar foreground color.
- `activityBar.inactiveForeground`: Activity Bar item foreground when inactive.
- `activityBar.border`: Activity Bar border with Side Bar.
- `activityBarBadge.background`: Activity notification badge background.
- `activityBarBadge.foreground`: Activity notification badge foreground.
- `activityBar.activeBorder`: Activity Bar active indicator border.
- `activityBar.activeBackground`: Activity Bar background for active element.
- `activityBar.activeFocusBorder`: Activity bar focus border for active item.
- `activityBarTop.foreground`: Active foreground for item when on top.
- `activityBarTop.activeBorder`: Focus border for active item when on top.
- `activityBarTop.inactiveForeground`: Inactive foreground for item when on top.
- `activityBarTop.dropBorder`: Drag and drop feedback for items when on top.
- `activityBarTop.background`: Background color when on top/bottom.
- `activityBarTop.activeBackground`: Background for active item when on top/bottom.
- `activityWarningBadge.foreground`: Foreground color of warning activity badge.
- `activityWarningBadge.background`: Background color of warning activity badge.
- `activityErrorBadge.foreground`: Foreground color of error activity badge.
- `activityErrorBadge.background`: Background color of error activity badge.

## Profiles
- `profileBadge.background`: Profile badge background color.
- `profileBadge.foreground`: Profile badge foreground color.
- `profiles.sashBorder`: Color of Profiles editor splitview sash border.

## Side Bar
- `sideBar.background`: Side Bar background color.
- `sideBar.foreground`: Side Bar foreground color.
- `sideBar.border`: Side Bar border with editor.
- `sideBar.dropBackground`: Drag and drop feedback color.
- `sideBarTitle.foreground`: Side Bar title foreground color.
- `sideBarSectionHeader.background`: Side Bar section header background.
- `sideBarSectionHeader.foreground`: Side Bar section header foreground.
- `sideBarSectionHeader.border`: Side bar section header border.
- `sideBarActivityBarTop.border`: Border between activity bar and views.
- `sideBarTitle.background`: Side bar title background color.
- `sideBarTitle.border`: Side bar title border on bottom.
- `sideBarStickyScroll.background`: Background color of sticky scroll.
- `sideBarStickyScroll.border`: Border color of sticky scroll.
- `sideBarStickyScroll.shadow`: Shadow color of sticky scroll.

## Minimap
- `minimap.findMatchHighlight`: Highlight color for search matches.
- `minimap.selectionHighlight`: Highlight color for editor selection.
- `minimap.errorHighlight`: Highlight color for errors.
- `minimap.warningHighlight`: Highlight color for warnings.
- `minimap.background`: Minimap background color.
- `minimap.selectionOccurrenceHighlight`: Marker color for repeating selections.
- `minimap.foregroundOpacity`: Opacity of foreground elements.
- `minimap.infoHighlight`: Marker color for infos.
- `minimap.chatEditHighlight`: Color of pending edit regions.
- `minimapSlider.background`: Minimap slider background color.
- `minimapSlider.hoverBackground`: Minimap slider background when hovering.
- `minimapSlider.activeBackground`: Minimap slider background when clicked.
- `minimapGutter.addedBackground`: Gutter color for added content.
- `minimapGutter.modifiedBackground`: Gutter color for modified content.
- `minimapGutter.deletedBackground`: Gutter color for deleted content.
- `editorMinimap.inlineChatInserted`: Marker color for inline chat inserted content.

## Editor Groups & Tabs
- `editorGroup.border`: Color to separate editor groups.
- `editorGroup.dropBackground`: Background color when dragging editors.
- `editorGroupHeader.noTabsBackground`: Background of editor group header with single Tab.
- `editorGroupHeader.tabsBackground`: Background color of Tabs container.
- `editorGroupHeader.tabsBorder`: Border below editor tabs.
- `editorGroupHeader.border`: Border between editor group header and editor.
- `editorGroup.emptyBackground`: Background color of empty editor group.
- `editorGroup.focusedEmptyBorder`: Border color of focused empty editor group.
- `editorGroup.dropIntoPromptForeground`: Foreground color of drag prompt text.
- `editorGroup.dropIntoPromptBackground`: Background color of drag prompt text.
- `editorGroup.dropIntoPromptBorder`: Border color of drag prompt text.
- `tab.activeBackground`: Active Tab background in active group.
- `tab.unfocusedActiveBackground`: Active Tab background in inactive group.
- `tab.activeForeground`: Active Tab foreground in active group.
- `tab.border`: Border to separate Tabs.
- `tab.activeBorder`: Bottom border for active tab.
- `tab.selectedBorderTop`: Border to top of selected tab.
- `tab.selectedBackground`: Background of selected tab.
- `tab.selectedForeground`: Foreground of selected tab.
- `tab.dragAndDropBorder`: Border indicating tab insertion.
- `tab.unfocusedActiveBorder`: Bottom border for active tab in inactive group.
- `tab.activeBorderTop`: Top border for active tab.
- `tab.unfocusedActiveBorderTop`: Top border for active tab in inactive group.
- `tab.lastPinnedBorder`: Border on right of last pinned editor.
- `tab.inactiveBackground`: Inactive Tab background color.
- `tab.unfocusedInactiveBackground`: Inactive Tab background in unfocused group.
- `tab.inactiveForeground`: Inactive Tab foreground in active group.
- `tab.unfocusedActiveForeground`: Active tab foreground in inactive group.
- `tab.unfocusedInactiveForeground`: Inactive tab foreground in inactive group.
- `tab.hoverBackground`: Tab background when hovering.
- `tab.unfocusedHoverBackground`: Tab background in unfocused group when hovering.
- `tab.hoverForeground`: Tab foreground when hovering.
- `tab.unfocusedHoverForeground`: Tab foreground in unfocused group when hovering.
- `tab.hoverBorder`: Border to highlight tabs when hovering.
- `tab.unfocusedHoverBorder`: Border to highlight tabs in unfocused group when hovering.
- `tab.activeModifiedBorder`: Border on top of modified active tabs.
- `tab.inactiveModifiedBorder`: Border on top of modified inactive tabs.
- `tab.unfocusedActiveModifiedBorder`: Border on top of modified active tabs in unfocused group.
- `tab.unfocusedInactiveModifiedBorder`: Border on top of modified inactive tabs in unfocused group.
- `editorPane.background`: Background color of editor pane.
- `sideBySideEditor.horizontalBorder`: Color to separate editors side by side top to bottom.
- `sideBySideEditor.verticalBorder`: Color to separate editors side by side left to right.

## Editor Colors
- `editor.background`: Editor background color.
- `editor.foreground`: Editor default foreground color.
- `editorLineNumber.foreground`: Color of editor line numbers.
- `editorLineNumber.activeForeground`: Color of active editor line number.
- `editorLineNumber.dimmedForeground`: Color of final editor line when dimmed.
- `editorCursor.background`: Background color of editor cursor.
- `editorCursor.foreground`: Color of editor cursor.
- `editorMultiCursor.primary.foreground`: Color of primary multi-cursor.
- `editorMultiCursor.primary.background`: Background color of primary multi-cursor.
- `editorMultiCursor.secondary.foreground`: Color of secondary multi-cursors.
- `editorMultiCursor.secondary.background`: Background color of secondary multi-cursors.
- `editor.placeholder.foreground`: Foreground color of placeholder text.
- `editor.compositionBorder`: Border color for IME composition.
- `editor.selectionBackground`: Color of editor selection.
- `editor.selectionForeground`: Color of selected text for high contrast.
- `editor.inactiveSelectionBackground`: Color of selection in inactive editor.
- `editor.selectionHighlightBackground`: Color for regions with same content as selection.
- `editor.selectionHighlightBorder`: Border color for regions with same content as selection.
- `editor.wordHighlightBackground`: Background color of symbol during read-access.
- `editor.wordHighlightBorder`: Border color of symbol during read-access.
- `editor.wordHighlightStrongBackground`: Background color of symbol during write-access.
- `editor.wordHighlightStrongBorder`: Border color of symbol during write-access.
- `editor.wordHighlightTextBackground`: Background color of textual occurrence.
- `editor.wordHighlightTextBorder`: Border color of textual occurrence.
- `editor.findMatchBackground`: Color of current search match.
- `editor.findMatchForeground`: Text color of current search match.
- `editor.findMatchHighlightForeground`: Foreground color of other search matches.
- `editor.findMatchHighlightBackground`: Color of other search matches.
- `editor.findRangeHighlightBackground`: Color of range limiting search.
- `editor.findMatchBorder`: Border color of current search match.
- `editor.findMatchHighlightBorder`: Border color of other search matches.
- `editor.findRangeHighlightBorder`: Border color of range limiting search.
- `search.resultsInfoForeground`: Color of text in search view completion message.
- `searchEditor.findMatchBackground`: Color of editor's results.
- `searchEditor.findMatchBorder`: Border color of editor's results.
- `searchEditor.textInputBorder`: Search editor text input box border.
- `editor.hoverHighlightBackground`: Highlight below word for hover.
- `editor.lineHighlightBackground`: Background color for line at cursor.
- `editor.lineHighlightBorder`: Border color for line at cursor.
- `editorWatermark.foreground`: Foreground color for editor watermark labels.
- `editorUnicodeHighlight.border`: Border color for unicode highlights.
- `editorUnicodeHighlight.background`: Background color for unicode highlights.
- `editorLink.activeForeground`: Color of active links.
- `editor.rangeHighlightBackground`: Background color of highlighted ranges.
- `editor.rangeHighlightBorder`: Border color of highlighted ranges.
- `editor.symbolHighlightBackground`: Background color of highlighted symbol.
- `editor.symbolHighlightBorder`: Border color of highlighted symbol.
- `editorWhitespace.foreground`: Color of whitespace characters.
- `editorIndentGuide.background`: Color of editor indentation guides.
- `editorIndentGuide.background1`: Color of editor indentation guides (1).
- `editorIndentGuide.background2`: Color of editor indentation guides (2).
- `editorIndentGuide.background3`: Color of editor indentation guides (3).
- `editorIndentGuide.background4`: Color of editor indentation guides (4).
- `editorIndentGuide.background5`: Color of editor indentation guides (5).
- `editorIndentGuide.background6`: Color of editor indentation guides (6).
- `editorIndentGuide.activeBackground`: Color of active editor indentation guide.
- `editorIndentGuide.activeBackground1`: Color of active editor indentation guides (1).
- `editorIndentGuide.activeBackground2`: Color of active editor indentation guides (2).
- `editorIndentGuide.activeBackground3`: Color of active editor indentation guides (3).
- `editorIndentGuide.activeBackground4`: Color of active editor indentation guides (4).
- `editorIndentGuide.activeBackground5`: Color of active editor indentation guides (5).
- `editorIndentGuide.activeBackground6`: Color of active editor indentation guides (6).
- `editorInlayHint.background`: Background color of inline hints.
- `editorInlayHint.foreground`: Foreground color of inline hints.
- `editorInlayHint.typeForeground`: Foreground color of inline hints for types.
- `editorInlayHint.typeBackground`: Background color of inline hints for types.
- `editorInlayHint.parameterForeground`: Foreground color of inline hints for parameters.
- `editorInlayHint.parameterBackground`: Background color of inline hints for parameters.
- `editorRuler.foreground`: Color of editor rulers.
- `editor.linkedEditingBackground`: Background color for linked editing mode.
- `editorCodeLens.foreground`: Foreground color of CodeLens.
- `editorLightBulb.foreground`: Color for lightbulb actions icon.
- `editorLightBulbAutoFix.foreground`: Color for lightbulb auto fix icon.
- `editorLightBulbAi.foreground`: Color for lightbulb AI icon.
- `editorBracketMatch.background`: Background color behind matching brackets.
- `editorBracketMatch.border`: Color for matching brackets boxes.
- `editorBracketHighlight.foreground1`: Foreground color of brackets (1).
- `editorBracketHighlight.foreground2`: Foreground color of brackets (2).
- `editorBracketHighlight.foreground3`: Foreground color of brackets (3).
- `editorBracketHighlight.foreground4`: Foreground color of brackets (4).
- `editorBracketHighlight.foreground5`: Foreground color of brackets (5).
- `editorBracketHighlight.foreground6`: Foreground color of brackets (6).
- `editorBracketHighlight.unexpectedBracket.foreground`: Foreground color of unexpected brackets.
- `editorBracketPairGuide.activeBackground1`: Background color of active bracket pair guides (1).
- `editorBracketPairGuide.activeBackground2`: Background color of active bracket pair guides (2).
- `editorBracketPairGuide.activeBackground3`: Background color of active bracket pair guides (3).
- `editorBracketPairGuide.activeBackground4`: Background color of active bracket pair guides (4).
- `editorBracketPairGuide.activeBackground5`: Background color of active bracket pair guides (5).
- `editorBracketPairGuide.activeBackground6`: Background color of active bracket pair guides (6).
- `editorBracketPairGuide.background1`: Background color of inactive bracket pair guides (1).
- `editorBracketPairGuide.background2`: Background color of inactive bracket pair guides (2).
- `editorBracketPairGuide.background3`: Background color of inactive bracket pair guides (3).
- `editorBracketPairGuide.background4`: Background color of inactive bracket pair guides (4).
- `editorBracketPairGuide.background5`: Background color of inactive bracket pair guides (5).
- `editorBracketPairGuide.background6`: Background color of inactive bracket pair guides (6).
- `editor.foldBackground`: Background color for folded ranges.
- `editor.foldPlaceholderForeground`: Color of collapsed text.
- `editorOverviewRuler.background`: Background color of editor overview ruler.
- `editorOverviewRuler.border`: Color of overview ruler border.
- `editorOverviewRuler.findMatchForeground`: Overview ruler marker for find matches.
- `editorOverviewRuler.rangeHighlightForeground`: Overview ruler marker for highlighted ranges.
- `editorOverviewRuler.selectionHighlightForeground`: Overview ruler marker for selection highlights.
- `editorOverviewRuler.wordHighlightForeground`: Overview ruler marker for symbol highlights.
- `editorOverviewRuler.wordHighlightStrongForeground`: Overview ruler marker for write-access symbols.
- `editorOverviewRuler.wordHighlightTextForeground`: Overview ruler marker for textual occurrences.
- `editorOverviewRuler.modifiedForeground`: Overview ruler marker for modified content.
- `editorOverviewRuler.addedForeground`: Overview ruler marker for added content.
- `editorOverviewRuler.deletedForeground`: Overview ruler marker for deleted content.
- `editorOverviewRuler.errorForeground`: Overview ruler marker for errors.
- `editorOverviewRuler.warningForeground`: Overview ruler marker for warnings.
- `editorOverviewRuler.infoForeground`: Overview ruler marker for infos.
- `editorOverviewRuler.bracketMatchForeground`: Overview ruler marker for matching brackets.
- `editorOverviewRuler.inlineChatInserted`: Overview ruler marker for inline chat inserted content.
- `editorOverviewRuler.inlineChatRemoved`: Overview ruler marker for inline chat removed content.
- `editorError.foreground`: Foreground color of error squiggles.
- `editorError.border`: Border color of error boxes.
- `editorError.background`: Background color of error text.
- `editorWarning.foreground`: Foreground color of warning squiggles.
- `editorWarning.border`: Border color of warning boxes.
- `editorWarning.background`: Background color of warning text.
- `editorInfo.foreground`: Foreground color of info squiggles.
- `editorInfo.border`: Border color of info boxes.
- `editorInfo.background`: Background color of info text.
- `editorHint.foreground`: Foreground color of hints.
- `editorHint.border`: Border color of hint boxes.
- `problemsErrorIcon.foreground`: Color for problems error icon.
- `problemsWarningIcon.foreground`: Color for problems warning icon.
- `problemsInfoIcon.foreground`: Color for problems info icon.
- `editorUnnecessaryCode.border`: Border color of unnecessary code.
- `editorUnnecessaryCode.opacity`: Opacity of unnecessary code.
- `editorGutter.background`: Background color of editor gutter.
- `editorGutter.modifiedBackground`: Gutter background for modified lines.
- `editorGutter.modifiedSecondaryBackground`: Gutter secondary background for modified lines.
- `editorGutter.addedBackground`: Gutter background for added lines.
- `editorGutter.addedSecondaryBackground`: Gutter secondary background for added lines.
- `editorGutter.deletedBackground`: Gutter background for deleted lines.
- `editorGutter.deletedSecondaryBackground`: Gutter secondary background for deleted lines.
- `editorGutter.commentRangeForeground`: Gutter decoration for commenting ranges.
- `editorGutter.commentGlyphForeground`: Gutter decoration for commenting glyphs.
- `editorGutter.commentUnresolvedGlyphForeground`: Gutter decoration for unresolved comment threads.
- `editorGutter.foldingControlForeground`: Color of folding control.
- `editorGutter.itemGlyphForeground`: Gutter decoration for item glyphs.
- `editorGutter.itemBackground`: Gutter decoration for item background.
- `editorCommentsWidget.resolvedBorder`: Border color for resolved comments.
- `editorCommentsWidget.unresolvedBorder`: Border color for unresolved comments.
- `editorCommentsWidget.rangeBackground`: Background color for comment ranges.
- `editorCommentsWidget.rangeActiveBackground`: Background color for selected comment range.
- `editorCommentsWidget.replyInputBackground`: Background color for comment reply input.
- `inlineEdit.gutterIndicator.primaryBorder`: Border color for primary inline edit gutter indicator.
- `inlineEdit.gutterIndicator.primaryForeground`: Foreground color for primary inline edit gutter indicator.
- `inlineEdit.gutterIndicator.primaryBackground`: Background color for primary inline edit gutter indicator.
- `inlineEdit.gutterIndicator.secondaryBorder`: Border color for secondary inline edit gutter indicator.
- `inlineEdit.gutterIndicator.secondaryForeground`: Foreground color for secondary inline edit gutter indicator.
- `inlineEdit.gutterIndicator.secondaryBackground`: Background color for secondary inline edit gutter indicator.
- `inlineEdit.gutterIndicator.successfulBorder`: Border color for successful inline edit gutter indicator.
- `inlineEdit.gutterIndicator.successfulForeground`: Foreground color for successful inline edit gutter indicator.
- `inlineEdit.gutterIndicator.successfulBackground`: Background color for successful inline edit gutter indicator.
- `inlineEdit.gutterIndicator.background`: Background color for inline edit gutter indicator.
- `inlineEdit.originalBackground`: Background color for original text in inline edits.
- `inlineEdit.modifiedBackground`: Background color for modified text in inline edits.
- `inlineEdit.originalChangedLineBackground`: Background color for changed lines in original text.
- `inlineEdit.originalChangedTextBackground`: Overlay color for changed text in original text.
- `inlineEdit.modifiedChangedLineBackground`: Background color for changed lines in modified text.
- `inlineEdit.modifiedChangedTextBackground`: Overlay color for changed text in modified text.
- `inlineEdit.originalBorder`: Border color for original text in inline edits.
- `inlineEdit.modifiedBorder`: Border color for modified text in inline edits.
- `inlineEdit.tabWillAcceptModifiedBorder`: Modified border color when tab will accept.
- `inlineEdit.tabWillAcceptOriginalBorder`: Original border color when tab will accept.

## Diff Editor Colors
- `diffEditor.insertedTextBackground`: Background color for inserted text.
- `diffEditor.insertedTextBorder`: Outline color for inserted text.
- `diffEditor.removedTextBackground`: Background color for removed text.
- `diffEditor.removedTextBorder`: Outline color for removed text.
- `diffEditor.border`: Border color between editors.
- `diffEditor.diagonalFill`: Color of diagonal fill.
- `diffEditor.insertedLineBackground`: Background color for inserted lines.
- `diffEditor.removedLineBackground`: Background color for removed lines.
- `diffEditorGutter.insertedLineBackground`: Background color for inserted margin.
- `diffEditorGutter.removedLineBackground`: Background color for removed margin.
- `diffEditorOverview.insertedForeground`: Overview ruler for inserted content.
- `diffEditorOverview.removedForeground`: Overview ruler for removed content.
- `diffEditor.unchangedRegionBackground`: Background color of unchanged blocks.
- `diffEditor.unchangedRegionForeground`: Foreground color of unchanged blocks.
- `diffEditor.unchangedRegionShadow`: Color of shadow around unchanged regions.
- `diffEditor.unchangedCodeBackground`: Background color of unchanged code.
- `diffEditor.move.border`: Border color for moved text.
- `diffEditor.moveActive.border`: Active border color for moved text.
- `multiDiffEditor.headerBackground`: Background color of multi file diff editor header.
- `multiDiffEditor.background`: Background color of multi file diff editor.
- `multiDiffEditor.border`: Border color of multi file diff editor.

## Chat Colors
- `chat.requestBorder`: Border color of chat request.
- `chat.requestBackground`: Background color of chat request.
- `chat.slashCommandBackground`: Background color of chat slash command.
- `chat.slashCommandForeground`: Foreground color of chat slash command.
- `chat.avatarBackground`: Background color of chat avatar.
- `chat.avatarForeground`: Foreground color of chat avatar.
- `chat.editedFileForeground`: Foreground color of edited file in list.
- `chat.linesAddedForeground`: Foreground color of lines added in code block pill.
- `chat.linesRemovedForeground`: Foreground color of lines removed in code block pill.
- `chat.requestCodeBorder`: Border color of code blocks in request.
- `chat.requestBubbleBackground`: Background color of chat request bubble.
- `chat.requestBubbleHoverBackground`: Background color of chat request bubble on hover.
- `chat.checkpointSeparator`: Chat checkpoint separator color.
- `chatManagement.sashBorder`: Color of Chat Management editor splitview sash border.

## Inline Chat Colors
- `inlineChat.background`: Background color of interactive editor widget.
- `inlineChat.foreground`: Foreground color of interactive editor widget.
- `inlineChat.border`: Border color of interactive editor widget.
- `inlineChat.shadow`: Shadow color of interactive editor widget.
- `inlineChatInput.border`: Border color of interactive editor input.
- `inlineChatInput.focusBorder`: Border color of interactive editor input when focused.
- `inlineChatInput.placeholderForeground`: Foreground color of input placeholder.
- `inlineChatInput.background`: Background color of interactive editor input.
- `inlineChatDiff.inserted`: Background color of inserted text in input.
- `inlineChatDiff.removed`: Background color of removed text in input.

## Panel Chat Colors
- `interactive.activeCodeBorder`: Border color for current interactive code cell when focused.
- `interactive.inactiveCodeBorder`: Border color for current interactive code cell when not focused.

## Editor Widget Colors
- `editorWidget.foreground`: Foreground color of editor widgets.
- `editorWidget.background`: Background color of editor widgets.
- `editorWidget.border`: Border color of editor widget.
- `editorWidget.resizeBorder`: Border color of resize bar.
- `editorSuggestWidget.background`: Background color of suggestion widget.
- `editorSuggestWidget.border`: Border color of suggestion widget.
- `editorSuggestWidget.foreground`: Foreground color of suggestion widget.
- `editorSuggestWidget.focusHighlightForeground`: Color of match highlights in focused item.
- `editorSuggestWidget.highlightForeground`: Color of match highlights.
- `editorSuggestWidget.selectedBackground`: Background color of selected entry.
- `editorSuggestWidget.selectedForeground`: Foreground color of selected entry.
- `editorSuggestWidget.selectedIconForeground`: Icon foreground of selected entry.
- `editorSuggestWidgetStatus.foreground`: Foreground color of suggest widget status.
- `editorHoverWidget.foreground`: Foreground color of editor hover.
- `editorHoverWidget.background`: Background color of editor hover.
- `editorHoverWidget.border`: Border color of editor hover.
- `editorHoverWidget.highlightForeground`: Foreground color of active item in parameter hint.
- `editorHoverWidget.statusBarBackground`: Background color of editor hover status bar.
- `editorGhostText.border`: Border color of ghost text.
- `editorGhostText.background`: Background color of ghost text.
- `editorGhostText.foreground`: Foreground color of ghost text.
- `editorStickyScroll.background`: Editor sticky scroll background color.
- `editorStickyScroll.border`: Border color of sticky scroll.
- `editorStickyScroll.shadow`: Shadow color of sticky scroll.
- `editorStickyScrollGutter.background`: Background color of gutter part of sticky scroll.
- `editorStickyScrollHover.background`: Editor sticky scroll on hover background color.
- `debugExceptionWidget.background`: Exception widget background color.
- `debugExceptionWidget.border`: Exception widget border color.
- `editorMarkerNavigation.background`: Editor marker navigation widget background.
- `editorMarkerNavigationError.background`: Editor marker navigation widget error color.
- `editorMarkerNavigationWarning.background`: Editor marker navigation widget warning color.
- `editorMarkerNavigationInfo.background`: Editor marker navigation widget info color.
- `editorMarkerNavigationError.headerBackground`: Editor marker navigation widget error heading background.
- `editorMarkerNavigationWarning.headerBackground`: Editor marker navigation widget warning heading background.
- `editorMarkerNavigationInfo.headerBackground`: Editor marker navigation widget info heading background.

## Peek View Colors
- `peekView.border`: Color of peek view borders and arrow.
- `peekViewEditor.background`: Background color of peek view editor.
- `peekViewEditorGutter.background`: Background color of gutter in peek view editor.
- `peekViewEditor.matchHighlightBackground`: Match highlight color in peek view editor.
- `peekViewEditor.matchHighlightBorder`: Match highlight border color in peek view editor.
- `peekViewResult.background`: Background color of peek view result list.
- `peekViewResult.fileForeground`: Foreground color for file nodes.
- `peekViewResult.lineForeground`: Foreground color for line nodes.
- `peekViewResult.matchHighlightBackground`: Match highlight color in result list.
- `peekViewResult.selectionBackground`: Background color of selected entry.
- `peekViewResult.selectionForeground`: Foreground color of selected entry.
- `peekViewTitle.background`: Background color of peek view title area.
- `peekViewTitleDescription.foreground`: Color of peek view title info.
- `peekViewTitleLabel.foreground`: Color of peek view title.
- `peekViewEditorStickyScroll.background`: Background color of sticky scroll in peek view editor.
- `peekViewEditorStickyScrollGutter.background`: Background color of gutter part of sticky scroll in peek view editor.

## Merge Conflicts Colors
- `merge.currentHeaderBackground`: Current header background in inline conflicts.
- `merge.currentContentBackground`: Current content background in inline conflicts.
- `merge.incomingHeaderBackground`: Incoming header background in inline conflicts.
- `merge.incomingContentBackground`: Incoming content background in inline conflicts.
- `merge.border`: Border color on headers and splitter.
- `merge.commonContentBackground`: Common ancestor content background.
- `merge.commonHeaderBackground`: Common ancestor header background.
- `editorOverviewRuler.currentContentForeground`: Current overview ruler foreground.
- `editorOverviewRuler.incomingContentForeground`: Incoming overview ruler foreground.
- `editorOverviewRuler.commonContentForeground`: Common ancestor overview ruler foreground.
- `editorOverviewRuler.commentForeground`: Overview ruler decoration for resolved comments.
- `editorOverviewRuler.commentUnresolvedForeground`: Overview ruler decoration for unresolved comments.
- `mergeEditor.change.background`: Background color for changes.
- `mergeEditor.change.word.background`: Background color for word changes.
- `mergeEditor.conflict.unhandledUnfocused.border`: Border color of unhandled unfocused conflicts.
- `mergeEditor.conflict.unhandledFocused.border`: Border color of unhandled focused conflicts.
- `mergeEditor.conflict.handledUnfocused.border`: Border color of handled unfocused conflicts.
- `mergeEditor.conflict.handledFocused.border`: Border color of handled focused conflicts.
- `mergeEditor.conflict.handled.minimapOverViewRuler`: Foreground color for changes in input 1.
- `mergeEditor.conflict.unhandled.minimapOverViewRuler`: Foreground color for changes in input 1.
- `mergeEditor.conflictingLines.background`: Background of "Conflicting Lines" text.
- `mergeEditor.changeBase.background`: Background color for changes in base.
- `mergeEditor.changeBase.word.background`: Background color for word changes in base.
- `mergeEditor.conflict.input1.background`: Background color of decorations in input 1.
- `mergeEditor.conflict.input2.background`: Background color of decorations in input 2.

## Panel Colors
- `panel.background`: Panel background color.
- `panel.border`: Panel border color.
- `panel.dropBorder`: Drag and drop feedback color.
- `panelTitle.activeBorder`: Border color for active panel title.
- `panelTitle.activeForeground`: Title color for active panel.
- `panelTitle.inactiveForeground`: Title color for inactive panel.
- `panelTitle.border`: Panel title border on bottom.
- `panelTitleBadge.background`: Panel title badge background color.
- `panelTitleBadge.foreground`: Panel title badge foreground color.
- `panelInput.border`: Input box border for inputs in panel.
- `panelSection.border`: Panel section border color.
- `panelSection.dropBackground`: Drag and drop feedback color for sections.
- `panelSectionHeader.background`: Panel section header background color.
- `panelSectionHeader.foreground`: Panel section header foreground color.
- `panelStickyScroll.background`: Background color of sticky scroll in panel.
- `panelStickyScroll.border`: Border color of sticky scroll in panel.
- `panelStickyScroll.shadow`: Shadow color of sticky scroll in panel.
- `panelSectionHeader.border`: Panel section header border color.
- `outputView.background`: Output view background color.
- `outputViewStickyScroll.background`: Output view sticky scroll background color.

## Status Bar Colors
- `statusBar.background`: Standard Status Bar background color.
- `statusBar.foreground`: Status Bar foreground color.
- `statusBar.border`: Status Bar border color.
- `statusBar.debuggingBackground`: Status Bar background when debugging.
- `statusBar.debuggingForeground`: Status Bar foreground when debugging.
- `statusBar.debuggingBorder`: Status Bar border when debugging.
- `statusBar.noFolderForeground`: Status Bar foreground when no folder.
- `statusBar.noFolderBackground`: Status Bar background when no folder.
- `statusBar.noFolderBorder`: Status Bar border when no folder.
- `statusBarItem.activeBackground`: Status Bar item background when clicking.
- `statusBarItem.hoverForeground`: Status bar item foreground when hovering.
- `statusBarItem.hoverBackground`: Status Bar item background when hovering.
- `statusBarItem.prominentForeground`: Status Bar prominent items foreground color.
- `statusBarItem.prominentBackground`: Status Bar prominent items background color.
- `statusBarItem.prominentHoverForeground`: Status bar prominent items foreground when hovering.
- `statusBarItem.prominentHoverBackground`: Status Bar prominent items background when hovering.
- `statusBarItem.remoteBackground`: Background color for remote indicator.
- `statusBarItem.remoteForeground`: Foreground color for remote indicator.
- `statusBarItem.remoteHoverBackground`: Background color for remote indicator when hovering.
- `statusBarItem.remoteHoverForeground`: Foreground color for remote indicator when hovering.
- `statusBarItem.errorBackground`: Status bar error items background color.
- `statusBarItem.errorForeground`: Status bar error items foreground color.
- `statusBarItem.errorHoverBackground`: Status bar error items background when hovering.
- `statusBarItem.errorHoverForeground`: Status bar error items foreground when hovering.
- `statusBarItem.warningBackground`: Status bar warning items background color.
- `statusBarItem.warningForeground`: Status bar warning items foreground color.
- `statusBarItem.warningHoverBackground`: Status bar warning items background when hovering.
- `statusBarItem.warningHoverForeground`: Status bar warning items foreground when hovering.
- `statusBarItem.compactHoverBackground`: Status bar item background when hovering item with two hovers.
- `statusBarItem.focusBorder`: Status bar item border when focused.
- `statusBar.focusBorder`: Status bar border when focused.
- `statusBarItem.offlineBackground`: Status bar item background when offline.
- `statusBarItem.offlineForeground`: Status bar item foreground when offline.
- `statusBarItem.offlineHoverForeground`: Status bar item foreground hover when offline.
- `statusBarItem.offlineHoverBackground`: Status bar item background hover when offline.

## Title Bar Colors
- `titleBar.activeBackground`: Title Bar background when active.
- `titleBar.activeForeground`: Title Bar foreground when active.
- `titleBar.inactiveBackground`: Title Bar background when inactive.
- `titleBar.inactiveForeground`: Title Bar foreground when inactive.
- `titleBar.border`: Title bar border color.

## Menu Bar Colors
- `menubar.selectionForeground`: Foreground color of selected menu item.
- `menubar.selectionBackground`: Background color of selected menu item.
- `menubar.selectionBorder`: Border color of selected menu item.
- `menu.foreground`: Foreground color of menu items.
- `menu.background`: Background color of menu items.
- `menu.selectionForeground`: Foreground color of selected menu item in menus.
- `menu.selectionBackground`: Background color of selected menu item in menus.
- `menu.selectionBorder`: Border color of selected menu item in menus.
- `menu.separatorBackground`: Color of separator menu item.
- `menu.border`: Border color of menus.

## Command Center Colors
- `commandCenter.foreground`: Foreground color of Command Center.
- `commandCenter.activeForeground`: Active foreground color of Command Center.
- `commandCenter.background`: Background color of Command Center.
- `commandCenter.activeBackground`: Active background color of Command Center.
- `commandCenter.border`: Border color of Command Center.
- `commandCenter.inactiveForeground`: Foreground color when inactive.
- `commandCenter.inactiveBorder`: Border color when inactive.
- `commandCenter.activeBorder`: Active border color of Command Center.
- `commandCenter.debuggingBackground`: Command Center background when debugging.

## Notification Colors
- `notificationCenter.border`: Notification Center border color.
- `notificationCenterHeader.foreground`: Notification Center header foreground color.
- `notificationCenterHeader.background`: Notification Center header background color.
- `notificationToast.border`: Notification toast border color.
- `notifications.foreground`: Notification foreground color.
- `notifications.background`: Notification background color.
- `notifications.border`: Notification border color.
- `notificationLink.foreground`: Notification links foreground color.
- `notificationsErrorIcon.foreground`: Color for notification error icon.
- `notificationsWarningIcon.foreground`: Color for notification warning icon.
- `notificationsInfoIcon.foreground`: Color for notification info icon.

## Banner Colors
- `banner.background`: Banner background color.
- `banner.foreground`: Banner foreground color.
- `banner.iconForeground`: Color for icon in banner.

## Extensions Colors
- `extensionButton.prominentForeground`: Extension view button foreground.
- `extensionButton.prominentBackground`: Extension view button background.
- `extensionButton.prominentHoverBackground`: Extension view button hover background.
- `extensionButton.background`: Button background for extension actions.
- `extensionButton.foreground`: Button foreground for extension actions.
- `extensionButton.hoverBackground`: Button hover background for extension actions.
- `extensionButton.separator`: Button separator for extension actions.
- `extensionBadge.remoteBackground`: Background color for remote badge.
- `extensionBadge.remoteForeground`: Foreground color for remote badge.
- `extensionIcon.starForeground`: Icon color for extension ratings.
- `extensionIcon.verifiedForeground`: Icon color for verified publisher.
- `extensionIcon.preReleaseForeground`: Icon color for pre-release extension.
- `extensionIcon.sponsorForeground`: Icon color for extension sponsor.
- `extensionIcon.privateForeground`: Icon color for private extensions.
- `mcpIcon.starForeground`: Icon color for mcp starred.

## Quick Picker Colors
- `pickerGroup.border`: Quick picker color for grouping borders.
- `pickerGroup.foreground`: Quick picker color for grouping labels.
- `quickInput.background`: Quick input background color.
- `quickInput.foreground`: Quick input foreground color.
- `quickInputList.focusBackground`: Quick picker background for focused item.
- `quickInputList.focusForeground`: Quick picker foreground for focused item.
- `quickInputList.focusIconForeground`: Quick picker icon foreground for focused item.
- `quickInputTitle.background`: Quick picker title background color.

## Keybinding Label Colors
- `keybindingLabel.background`: Keybinding label background color.
- `keybindingLabel.foreground`: Keybinding label foreground color.
- `keybindingLabel.border`: Keybinding label border color.
- `keybindingLabel.bottomBorder`: Keybinding label border bottom color.

## Keyboard Shortcut Table Colors
- `keybindingTable.headerBackground`: Background color for table header.
- `keybindingTable.rowsBackground`: Background color for table alternating rows.

## Integrated Terminal Colors
- `terminal.background`: Background of terminal viewport.
- `terminal.border`: Color of border separating split panes.
- `terminal.foreground`: Default foreground color of terminal.
- `terminal.ansiBlack`: 'Black' ANSI color.
- `terminal.ansiBlue`: 'Blue' ANSI color.
- `terminal.ansiBrightBlack`: 'BrightBlack' ANSI color.
- `terminal.ansiBrightBlue`: 'BrightBlue' ANSI color.
- `terminal.ansiBrightCyan`: 'BrightCyan' ANSI color.
- `terminal.ansiBrightGreen`: 'BrightGreen' ANSI color.
- `terminal.ansiBrightMagenta`: 'BrightMagenta' ANSI color.
- `terminal.ansiBrightRed`: 'BrightRed' ANSI color.
- `terminal.ansiBrightWhite`: 'BrightWhite' ANSI color.
- `terminal.ansiBrightYellow`: 'BrightYellow' ANSI color.
- `terminal.ansiCyan`: 'Cyan' ANSI color.
- `terminal.ansiGreen`: 'Green' ANSI color.
- `terminal.ansiMagenta`: 'Magenta' ANSI color.
- `terminal.ansiRed`: 'Red' ANSI color.
- `terminal.ansiWhite`: 'White' ANSI color.
- `terminal.ansiYellow`: 'Yellow' ANSI color.
- `terminal.selectionBackground`: Selection background color.
- `terminal.selectionForeground`: Selection foreground color.
- `terminal.inactiveSelectionBackground`: Selection background when inactive.
- `terminal.findMatchBackground`: Color of current search match.
- `terminal.findMatchBorder`: Border color of current search match.
- `terminal.findMatchHighlightBackground`: Color of other search matches.
- `terminal.findMatchHighlightBorder`: Border color of other search matches.
- `terminal.hoverHighlightBackground`: Color of highlight when hovering link.
- `terminalCursor.background`: Background color of terminal cursor.
- `terminalCursor.foreground`: Foreground color of terminal cursor.
- `terminal.dropBackground`: Background color when dragging on terminals.
- `terminal.tab.activeBorder`: Border on side of terminal tab.
- `terminalCommandDecoration.defaultBackground`: Background color for default commands.
- `terminalCommandDecoration.successBackground`: Background color for successful commands.
- `terminalCommandDecoration.errorBackground`: Background color for error commands.
- `terminalOverviewRuler.cursorForeground`: Overview ruler cursor color.
- `terminalOverviewRuler.findMatchForeground`: Overview ruler marker for find matches.
- `terminalStickyScroll.background`: Background color of sticky scroll overlay.
- `terminalStickyScroll.border`: Border of sticky scroll overlay.
- `terminalStickyScrollHover.background`: Background color when hovered.
- `terminal.initialHintForeground`: Foreground color of initial hint.
- `terminalOverviewRuler.border`: Overview ruler left-side border color.
- `terminalCommandGuide.foreground`: Foreground color of command guide.
- `terminalSymbolIcon.aliasForeground`: Foreground color for alias icon.
- `terminalSymbolIcon.branchForeground`: Foreground color for branch icon.
- `terminalSymbolIcon.commitForeground`: Foreground color for commit icon.
- `terminalSymbolIcon.flagForeground`: Foreground color for flag icon.
- `terminalSymbolIcon.optionForeground`: Foreground color for option icon.
- `terminalSymbolIcon.optionValueForeground`: Foreground color for enum member icon.
- `terminalSymbolIcon.methodForeground`: Foreground color for method icon.
- `terminalSymbolIcon.argumentForeground`: Foreground color for argument icon.
- `terminalSymbolIcon.inlineSuggestionForeground`: Foreground color for inline suggestion icon.
- `terminalSymbolIcon.fileForeground`: Foreground color for file icon.
- `terminalSymbolIcon.folderForeground`: Foreground color for folder icon.
- `terminalSymbolIcon.pullRequestDoneForeground`: Foreground color for completed pull request icon.
- `terminalSymbolIcon.pullRequestForeground`: Foreground color for pull request icon.
- `terminalSymbolIcon.remoteForeground`: Foreground color for remote icon.
- `terminalSymbolIcon.stashForeground`: Foreground color for stash icon.
- `terminalSymbolIcon.symbolText`: Foreground color for plaintext suggestion.
- `terminalSymbolIcon.symbolicLinkFileForeground`: Foreground color for symbolic link file icon.
- `terminalSymbolIcon.symbolicLinkFolderForeground`: Foreground color for symbolic link folder icon.
- `terminalSymbolIcon.tagForeground`: Foreground color for tag icon.

## Debug Colors
- `debugToolBar.background`: Debug toolbar background color.
- `debugToolBar.border`: Debug toolbar border color.
- `editor.stackFrameHighlightBackground`: Background color of top stack frame highlight.
- `editor.focusedStackFrameHighlightBackground`: Background color of focused stack frame highlight.
- `editor.inlineValuesForeground`: Color for debug inline value text.
- `editor.inlineValuesBackground`: Color for debug inline value background.
- `debugView.exceptionLabelForeground`: Foreground color for exception label in CALL STACK.
- `debugView.exceptionLabelBackground`: Background color for exception label in CALL STACK.
- `debugView.stateLabelForeground`: Foreground color for session/thread state label.
- `debugView.stateLabelBackground`: Background color for session/thread state label.
- `debugView.valueChangedHighlight`: Color for value changes in debug views.
- `debugTokenExpression.name`: Foreground color for token names in debug views.
- `debugTokenExpression.value`: Foreground color for token values in debug views.
- `debugTokenExpression.string`: Foreground color for strings in debug views.
- `debugTokenExpression.boolean`: Foreground color for booleans in debug views.
- `debugTokenExpression.number`: Foreground color for numbers in debug views.
- `debugTokenExpression.error`: Foreground color for expression errors in debug views.
- `debugTokenExpression.type`: Foreground color for token types in debug views.

## Testing Colors
- `testing.runAction`: Color for 'run' icons in editor.
- `testing.iconErrored`: Color for 'Errored' icon in test explorer.
- `testing.iconFailed`: Color for 'failed' icon in test explorer.
- `testing.iconPassed`: Color for 'passed' icon in test explorer.
- `testing.iconQueued`: Color for 'Queued' icon in test explorer.
- `testing.iconUnset`: Color for 'Unset' icon in test explorer.
- `testing.iconSkipped`: Color for 'Skipped' icon in test explorer.
- `testing.iconErrored.retired`: Retired color for 'Errored' icon.
- `testing.iconFailed.retired`: Retired color for 'failed' icon.
- `testing.iconPassed.retired`: Retired color for 'passed' icon.
- `testing.iconQueued.retired`: Retired color for 'Queued' icon.
- `testing.iconUnset.retired`: Retired color for 'Unset' icon.
- `testing.iconSkipped.retired`: Retired color for 'Skipped' icon.
- `testing.peekBorder`: Color of peek view borders and arrow.
- `testing.peekHeaderBackground`: Color of peek view borders and arrow.
- `testing.message.error.lineBackground`: Margin color beside error messages.
- `testing.message.info.decorationForeground`: Text color of info messages.
- `testing.message.info.lineBackground`: Margin color beside info messages.
- `testing.messagePeekBorder`: Color of peek view borders when peeking message.
- `testing.messagePeekHeaderBackground`: Color of peek view borders when peeking message.
- `testing.coveredBackground`: Background color of covered text.
- `testing.coveredBorder`: Border color of covered text.
- `testing.coveredGutterBackground`: Gutter color of covered regions.
- `testing.uncoveredBranchBackground`: Background of uncovered branch widget.
- `testing.uncoveredBackground`: Background color of uncovered text.
- `testing.uncoveredBorder`: Border color of uncovered text.
- `testing.uncoveredGutterBackground`: Gutter color of uncovered regions.
- `testing.coverCountBadgeBackground`: Background for execution count badge.
- `testing.coverCountBadgeForeground`: Foreground for execution count badge.
- `testing.message.error.badgeBackground`: Background color of error messages.
- `testing.message.error.badgeBorder`: Border color of error messages.
- `testing.message.error.badgeForeground`: Text color of error messages.

## Welcome Page Colors
- `welcomePage.background`: Background color for Welcome page.
- `welcomePage.progress.background`: Foreground color for progress bars.
- `welcomePage.progress.foreground`: Background color for progress bars.
- `welcomePage.tileBackground`: Background color for tiles.
- `welcomePage.tileHoverBackground`: Hover background color for tiles.
- `welcomePage.tileBorder`: Border color for tiles.
- `walkThrough.embeddedEditorBackground`: Background color for embedded editors.
- `walkthrough.stepTitle.foreground`: Foreground color of walkthrough step heading.

## Git Colors
- `gitDecoration.addedResourceForeground`: Color for added Git resources.
- `gitDecoration.modifiedResourceForeground`: Color for modified Git resources.
- `gitDecoration.deletedResourceForeground`: Color for deleted Git resources.
- `gitDecoration.renamedResourceForeground`: Color for renamed or copied Git resources.
- `gitDecoration.stageModifiedResourceForeground`: Color for staged modifications.
- `gitDecoration.stageDeletedResourceForeground`: Color for staged deletions.
- `gitDecoration.untrackedResourceForeground`: Color for untracked Git resources.
- `gitDecoration.ignoredResourceForeground`: Color for ignored Git resources.
- `gitDecoration.conflictingResourceForeground`: Color for conflicting Git resources.
- `gitDecoration.submoduleResourceForeground`: Color for submodule resources.
- `git.blame.editorDecorationForeground`: Color for blame editor decoration.

## Source Control Graph Colors
- `scmGraph.historyItemHoverLabelForeground`: History item hover label foreground color.
- `scmGraph.foreground1`: Source control graph foreground color (1).
- `scmGraph.foreground2`: Source control graph foreground color (2).
- `scmGraph.foreground3`: Source control graph foreground color (3).
- `scmGraph.foreground4`: Source control graph foreground color (4).
- `scmGraph.foreground5`: Source control graph foreground color (5).
- `scmGraph.historyItemHoverAdditionsForeground`: History item hover additions foreground color.
- `scmGraph.historyItemHoverDeletionsForeground`: History item hover deletions foreground color.
- `scmGraph.historyItemRefColor`: History item reference color.
- `scmGraph.historyItemRemoteRefColor`: History item remote reference color.
- `scmGraph.historyItemBaseRefColor`: History item base reference color.
- `scmGraph.historyItemHoverDefaultLabelForeground`: History item hover default label foreground color.
- `scmGraph.historyItemHoverDefaultLabelBackground`: History item hover default label background color.

## Settings Editor Colors
- `settings.headerForeground`: Foreground color for section header.
- `settings.modifiedItemIndicator`: Line indicating modified setting.
- `settings.dropdownBackground`: Dropdown background.
- `settings.dropdownForeground`: Dropdown foreground.
- `settings.dropdownBorder`: Dropdown border.
- `settings.dropdownListBorder`: Dropdown list border.
- `settings.checkboxBackground`: Checkbox background.
- `settings.checkboxForeground`: Checkbox foreground.
- `settings.checkboxBorder`: Checkbox border.
- `settings.rowHoverBackground`: Background color of settings row when hovered.
- `settings.textInputBackground`: Text input box background.
- `settings.textInputForeground`: Text input box foreground.
- `settings.textInputBorder`: Text input box border.
- `settings.numberInputBackground`: Number input box background.
- `settings.numberInputForeground`: Number input box foreground.
- `settings.numberInputBorder`: Number input box border.
- `settings.focusedRowBackground`: Background color of focused setting row.
- `settings.focusedRowBorder`: Color of row's top and bottom border when focused.
- `settings.headerBorder`: Color of header container border.
- `settings.sashBorder`: Color of Settings editor splitview sash border.
- `settings.settingsHeaderHoverForeground`: Foreground color for section header or hovered title.

## Breadcrumbs Colors
- `breadcrumb.foreground`: Color of breadcrumb items.
- `breadcrumb.background`: Background color of breadcrumb items.
- `breadcrumb.focusForeground`: Color of focused breadcrumb items.
- `breadcrumb.activeSelectionForeground`: Color of selected breadcrumb items.
- `breadcrumbPicker.background`: Background color of breadcrumb item picker.

## Snippets Colors
- `editor.snippetTabstopHighlightBackground`: Highlight background color of tabstop.
- `editor.snippetTabstopHighlightBorder`: Highlight border color of tabstop.
- `editor.snippetFinalTabstopHighlightBackground`: Highlight background color of final tabstop.
- `editor.snippetFinalTabstopHighlightBorder`: Highlight border color of final tabstop.

## Symbol Icons Colors
- `symbolIcon.arrayForeground`: Foreground color for array symbols.
- `symbolIcon.booleanForeground`: Foreground color for boolean symbols.
- `symbolIcon.classForeground`: Foreground color for class symbols.
- `symbolIcon.colorForeground`: Foreground color for color symbols.
- `symbolIcon.constantForeground`: Foreground color for constant symbols.
- `symbolIcon.constructorForeground`: Foreground color for constructor symbols.
- `symbolIcon.enumeratorForeground`: Foreground color for enumerator symbols.
- `symbolIcon.enumeratorMemberForeground`: Foreground color for enumerator member symbols.
- `symbolIcon.eventForeground`: Foreground color for event symbols.
- `symbolIcon.fieldForeground`: Foreground color for field symbols.
- `symbolIcon.fileForeground`: Foreground color for file symbols.
- `symbolIcon.folderForeground`: Foreground color for folder symbols.
- `symbolIcon.functionForeground`: Foreground color for function symbols.
- `symbolIcon.interfaceForeground`: Foreground color for interface symbols.
- `symbolIcon.keyForeground`: Foreground color for key symbols.
- `symbolIcon.keywordForeground`: Foreground color for keyword symbols.
- `symbolIcon.methodForeground`: Foreground color for method symbols.
- `symbolIcon.moduleForeground`: Foreground color for module symbols.
- `symbolIcon.namespaceForeground`: Foreground color for namespace symbols.
- `symbolIcon.nullForeground`: Foreground color for null symbols.
- `symbolIcon.numberForeground`: Foreground color for number symbols.
- `symbolIcon.objectForeground`: Foreground color for object symbols.
- `symbolIcon.operatorForeground`: Foreground color for operator symbols.
- `symbolIcon.packageForeground`: Foreground color for package symbols.
- `symbolIcon.propertyForeground`: Foreground color for property symbols.
- `symbolIcon.referenceForeground`: Foreground color for reference symbols.
- `symbolIcon.snippetForeground`: Foreground color for snippet symbols.
- `symbolIcon.stringForeground`: Foreground color for string symbols.
- `symbolIcon.structForeground`: Foreground color for struct symbols.
- `symbolIcon.textForeground`: Foreground color for text symbols.
- `symbolIcon.typeParameterForeground`: Foreground color for type parameter symbols.
- `symbolIcon.unitForeground`: Foreground color for unit symbols.
- `symbolIcon.variableForeground`: Foreground color for variable symbols.

## Debug Icons Colors
- `debugIcon.breakpointForeground`: Icon color for breakpoints.
- `debugIcon.breakpointDisabledForeground`: Icon color for disabled breakpoints.
- `debugIcon.breakpointUnverifiedForeground`: Icon color for unverified breakpoints.
- `debugIcon.breakpointCurrentStackframeForeground`: Icon color for current breakpoint stack frame.
- `debugIcon.breakpointStackframeForeground`: Icon color for all breakpoint stack frames.
- `debugIcon.startForeground`: Debug toolbar icon for start debugging.
- `debugIcon.pauseForeground`: Debug toolbar icon for pause.
- `debugIcon.stopForeground`: Debug toolbar icon for stop.
- `debugIcon.disconnectForeground`: Debug toolbar icon for disconnect.
- `debugIcon.restartForeground`: Debug toolbar icon for restart.
- `debugIcon.stepOverForeground`: Debug toolbar icon for step over.
- `debugIcon.stepIntoForeground`: Debug toolbar icon for step into.
- `debugIcon.stepOutForeground`: Debug toolbar icon for step over.
- `debugIcon.continueForeground`: Debug toolbar icon for continue.
- `debugIcon.stepBackForeground`: Debug toolbar icon for step back.
- `debugConsole.infoForeground`: Foreground color for info messages in debug REPL.
- `debugConsole.warningForeground`: Foreground color for warning messages in debug REPL.
- `debugConsole.errorForeground`: Foreground color for error messages in debug REPL.
- `debugConsole.sourceForeground`: Foreground color for source filenames in debug REPL.
- `debugConsoleInputIcon.foreground`: Foreground color for debug console input marker icon.

## Notebook Colors
- `notebook.editorBackground`: Notebook background color.
- `notebook.cellBorderColor`: Border color for notebook cells.
- `notebook.cellHoverBackground`: Background color of cell when hovered.
- `notebook.cellInsertionIndicator`: Color of notebook cell insertion indicator.
- `notebook.cellStatusBarItemHoverBackground`: Background color of cell status bar items.
- `notebook.cellToolbarSeparator`: Color of separator in cell bottom toolbar.
- `notebook.cellEditorBackground`: Color of notebook cell editor background.
- `notebook.focusedCellBackground`: Background color of cell when focused.
- `notebook.focusedCellBorder`: Color of cell's focus indicator borders.
- `notebook.focusedEditorBorder`: Color of notebook cell editor border.
- `notebook.inactiveFocusedCellBorder`: Color of cell's top and bottom border when focused while primary focus outside.
- `notebook.inactiveSelectedCellBorder`: Color of cell's borders when multiple cells selected.
- `notebook.outputContainerBackgroundColor`: Color of notebook output container background.
- `notebook.outputContainerBorderColor`: Border color of notebook output container.
- `notebook.selectedCellBackground`: Background color of cell when selected.
- `notebook.selectedCellBorder`: Color of cell's top and bottom border when selected but not focused.
- `notebook.symbolHighlightBackground`: Background color of highlighted cell.
- `notebookScrollbarSlider.activeBackground`: Notebook scrollbar slider background when clicked.
- `notebookScrollbarSlider.background`: Notebook scrollbar slider background color.
- `notebookScrollbarSlider.hoverBackground`: Notebook scrollbar slider background when hovering.
- `notebookStatusErrorIcon.foreground`: Error icon color of notebook cells.
- `notebookStatusRunningIcon.foreground`: Running icon color of notebook cells.
- `notebookStatusSuccessIcon.foreground`: Success icon color of notebook cells.
- `notebookEditorOverviewRuler.runningCellForeground`: Color of running cell decoration in overview ruler.

## Chart Colors
- `charts.foreground`: Contrast color for text in charts.
- `charts.lines`: Color for lines in charts.
- `charts.red`: Color for red elements in charts.
- `charts.blue`: Color for blue elements in charts.
- `charts.yellow`: Color for yellow elements in charts.
- `charts.orange`: Color for orange elements in charts.
- `charts.green`: Color for green elements in charts.
- `charts.purple`: Color for purple elements in charts.
- `chart.line`: Line color for the chart.
- `chart.axis`: Axis color for the chart.
- `chart.guide`: Guide line for the chart.

## Ports Colors
- `ports.iconRunningProcessForeground`: Color of icon for port with running process.

## Comments View Colors
- `commentsView.resolvedIcon`: Icon color for resolved comments.
- `commentsView.unresolvedIcon`: Icon color for unresolved comments.

## Action Bar Colors
- `actionBar.toggledBackground`: Background color for toggled action items.

## Simple Find Widget Colors
- `simpleFindWidget.sashBorder`: Border color of sash border.

## Gauge Colors
- `gauge.background`: Gauge background color.
- `gauge.foreground`: Gauge foreground color.
- `gauge.border`: Gauge border color.
- `gauge.warningBackground`: Gauge warning background color.
- `gauge.warningForeground`: Gauge warning foreground color.
- `gauge.errorBackground`: Gauge error background color.
- `gauge.errorForeground`: Gauge error foreground color.

## Markdown
- `markdownAlert.note.foreground`: Foreground color for note alerts.
- `markdownAlert.tip.foreground`: Foreground color for tip alerts.
- `markdownAlert.important.foreground`: Foreground color for important alerts.
- `markdownAlert.warning.foreground`: Foreground color for warning alerts.
- `markdownAlert.caution.foreground`: Foreground color for caution alerts.

## Extension Colors
Extension-defined colors are also available.