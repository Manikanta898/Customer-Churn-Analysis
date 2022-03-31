# firstone
this is first one
import java.awt.*;

class UndoableTextArea extends TextArea implements StateEditable

( private final static String KEY_STATE="UndoableTextAreaKey";

private boolean textChanged-false;

private UndoManager undoManager;

private StateEdit currentEdit;

public UndoableTextArea() (

super(); initUndoable();

public UndoableTextArea(String string) (

super(string); initUndoable();
