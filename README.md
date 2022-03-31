public UndoableTextArea(String string, int rows, int columns)

{ super(string, rows,columns); initUndoable();

} public UndoableTextArea(String string, int rows, int columns, int scrollbars)

super(string, rows, columns, scrollbars); initUndoable();

I public boolean undo(){

undoManager.undo(); return true;

{

try{
