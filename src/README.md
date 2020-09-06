## Quick Start

Install `prosemirror-utils` package from npm:

```sh
npm install prosemirror-utils
```

## Public API documentation

### Utils for working with `selection`

@findParentNode

@findParentNodeClosestToPos

@findParentDomRef

@hasParentNode

@findParentNodeOfType

@findParentNodeOfTypeClosestToPos

@hasParentNodeOfType

@findParentDomRefOfType

@findSelectedNodeOfType

@isNodeSelection

@findPositionOfNodeBefore

@findDomRefAtPos

### Utils for working with ProseMirror `node`

@flatten

@findChildren

@findTextNodes

@findInlineNodes

@findBlockNodes

@findChildrenByAttr

@findChildrenByType

@findChildrenByMark

@contains

### Utils for working with `table`

@findTable

@isCellSelection

@isColumnSelected

@isRowSelected

@isTableSelected

@getCellsInColumn

@getCellsInRow

@getCellsInTable

@selectColumn

@selectRow

@selectTable

@emptyCell

@addColumnAt

@moveRow

@moveColumn

@addRowAt

@cloneRowAt

@removeColumnAt

@removeRowAt

@removeTable

@removeSelectedColumns

@removeSelectedRows

@removeColumnClosestToPos

@removeRowClosestToPos

@findCellClosestToPos

@findCellRectClosestToPos

@forEachCellInColumn

@forEachCellInRow

@setCellAttrs

@createTable

@getSelectionRect

@getSelectionRangeInColumn

@getSelectionRangeInRow

### Utils for document transformation

@removeParentNodeOfType

@replaceParentNodeOfType

@removeSelectedNode

@replaceSelectedNode

@canInsert

@safeInsert

@setParentNodeMarkup

@selectParentNodeOfType

@removeNodeBefore

@setTextSelection

@convertTableNodeToArrayOfRows

@convertArrayOfRowsToTableNode

## License

* **Apache 2.0** : http://www.apache.org/licenses/LICENSE-2.0
