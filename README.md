# skDataGridCloner
Utility for copying or cloning (make the destination datagrid identical to the source datagrid) datagrids to another (or the same) stack. This may be best used as plugin for easy access.

skDataGridCloner is a utility for replicating datagrids especially for use with other stacks. Datagrids use a template substack where each card corresponds to a respective datagrid template and these need to follow the datagrid if copied to another stack.

Usage:
- Click on the source datagrid and click the **Source** button to assing it as source
- Click on a destination datagrid and click the **Destination** button to assign it. If no datagrid is selected, it will assume the destination is the current card of the topstack.
- If a destination datagrid is selected the option to _Clone_ the datagrid will be enabled - the destination will be changed to an exact copy of the source
- If no destination datagrid is selected and a card is selected instead, the option to _Copy_ the datagrid will be activated instead.
- If the mainstack of the destination has no Data Grid Templates substack, one will be created. The template card corresponding to the source is copied to the new or existing datagrid template substack and wired up with the datagrid group.
