#IfWinActive,
*RButton Up::

If (Toggle := !Toggle){

Send {Click Down Right}

}

Else{

Send {RButton up}

}

Return
~CapsLock::Suspend, Toggle
