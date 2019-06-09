# CapsLock_ChangeLanguage_Window
### Download AutoHotkey and Install -> https://autohotkey.com/download/
### You copy this
<hr/>
<pre><code>capslock::
KeyWait, capslock
if A_TimeSinceThisHotkey >= 250 ; in milliseconds.
SetCapsLockState, % (State:=!State) ? "On" : "Off"
else
Send, {vk15sc1F2}
return
</code></pre>
<hr/>

### and save anywhere. but file name finish .ahk e.g. CapsLockKorEng.ahk
### Push [Windows]+[R] and input shell:startup and input enter
### move your .ahk file on startup folder.
### finally, you double click .ahk file
## CapsLock Short Click -> Change Language
## CapsLock Long Click -> Upper or Lower
