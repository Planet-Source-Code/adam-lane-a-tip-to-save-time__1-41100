<div align="center">

## A Tip to save Time


</div>

### Description

This is a tip that will save many of you VB Programmers a lot of time. It is a piece of code that allows the user in one line of code to create a toggle system. Enjoy
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Adam Lane](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/adam-lane.md)
**Level**          |Beginner
**User Rating**    |3.1 (25 globes from 8 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__1-43.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/adam-lane-a-tip-to-save-time__1-41100/archive/master.zip)





### Source Code

<p><font face="Verdana"><small><small><small><u><b>A Tip to Save Time</b><br>
</u></small></small></small><b><small><small><small>by Adam Lane</small></small></small></b><br>
<small><small><small><br>
Say you want to make a toggle system, eg: You have a form and in that form you
have a Picture Box and a Command Button and you want to make a project where
whenever you click on the Command Button, the Picture Box will go
invisible/visible (opposite to what it's current state is). Instead of having to
write this boring code:</small></small></small><br>
<br>
</font><font face="Courier New"><small><small><small>Private Sub Command1_Click()<br>
    If Picture1.Visible = True Then<br>
        Picture1.Visible = False<br>
    ElseIf Picture1.Visible = False Then<br>
        Picture1.Visible = True<br>
    End If<br>
End Sub</small></small></small></font><font face="Verdana"><br>
<small><small><small><small>You can Replace it with this easy code:</small></small></small></small></font><small><small><small><small><font face="Courier New"><br>
<br>
Private Sub Command1_Click()
    Picture1.Visible = Not Picture1.Visible<br>
End Sub<br>
<small><small><small><small><small><br>
</small></small></small></small></small></font><font face="Verdana"><small>Now,
I know that code is simple and the majority of you probably already knew it. But
I know that there would be many people in the VB World that didn't.<br>
<br>
 - Adam Lane</small></font></small></small></small></small></p>

