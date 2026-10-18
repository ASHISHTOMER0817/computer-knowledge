# Microsoft Office

The ribbon is the command band. Font, alignment, and find are on **Home**.

## The suite


| Program    | Job                      | Extension |
| ---------- | ------------------------ | --------- |
| Word       | Documents                | `.docx`   |
| Excel      | Spreadsheets             | `.xlsx`   |
| PowerPoint | Slides                   | `.pptx`   |
| Access     | Database                 | `.accdb`  |
| Outlook    | Mail, calendar, contacts | —         |


Unsaved files are named `Document1`, `Book1`, or `Presentation1`. Word first shipped in 1983 as Multi-Tool Word. The first Office suite shipped in 1989.

## Microsoft Word

- **File** creates, opens, saves, and prints.
- **Quick Access Toolbar** holds Save, Undo, and Redo.
- **Ruler** sets indents and shows margins. Horizontal ruler: width and left/right. Vertical ruler: height and top/bottom.
- **Split box** is at the top of the vertical scroll bar.
- **Status bar** shows page, word count, and view. **Zoom** is at its right end.
- Enter starts a new paragraph. A new paragraph is left aligned. Word wraps lines by itself.


| Tab        | Holds                                                       |
| ---------- | ----------------------------------------------------------- |
| Home       | Cut, Copy, Paste, Font, Paragraph, Styles, Find and Replace |
| Insert     | Tables, pictures, charts, header and footer, symbols        |
| Layout     | Margins, orientation, size, columns, breaks                 |
| References | Contents, footnotes, index                                  |
| Mailings   | Mail merge                                                  |
| Review     | Spelling, thesaurus, comments, track changes                |
| View       | Read Mode, Print Layout, Web Layout, ruler, zoom            |


- Clipboard lives in memory.
- Font styles are regular, bold, italic, and bold-italic. Superscript is a character effect.
- Portrait is tall. Landscape is wide. Justify aligns to both margins.
- Indent is the gap between text and the page margin: first-line, hanging, and left/right.
- Header is the top margin. Footer is the bottom margin. Both print on every page by default.
- A soft page break is automatic. **Ctrl + Enter** is a manual page break.
- A section is a page-setup region. One section can cover many pages. After a section break, margins, orientation, and headers can differ. Page Setup applies to this section or the whole document.
- **Ctrl + S** saves. The first save, and any new name, uses the **Save As** dialog. **Ctrl + P** prints. **Ctrl + F2** is Print Preview.
- AutoCorrect fixes a stored list of typing mistakes as you type. Bullets are unordered. Numbering is ordered.


| Action                              | Shortcut                                                              |
| ----------------------------------- | --------------------------------------------------------------------- |
| New / Open / Save / Save As         | Ctrl + N / Ctrl + O (or Ctrl + F12) / Ctrl + S (or Shift + F12) / F12 |
| Print / Print Preview               | Ctrl + P / Ctrl + F2                                                  |
| Select all / Cut / Copy / Paste     | Ctrl + A / Ctrl + X / Ctrl + C / Ctrl + V                             |
| Undo / Redo                         | Ctrl + Z / Ctrl + Y                                                   |
| Bold / Italic / Underline           | Ctrl + B / Ctrl + I / Ctrl + U                                        |
| Left / Centre / Right / Justify     | Ctrl + L / Ctrl + E / Ctrl + R / Ctrl + J                             |
| 1.5 line spacing / Find / Hyperlink | Ctrl + 5 / Ctrl + F / Ctrl + K                                        |
| Spelling / Help                     | F7 / F1                                                               |
| Start or end of line                | Home / End                                                            |
| Start or end of document            | Ctrl + Home / Ctrl + End                                              |
| Delete word right / left            | Ctrl + Delete / Ctrl + Backspace                                      |
| Copy formatting                     | Ctrl + Shift + C                                                      |


## Microsoft Excel

A new workbook (`Book1.xlsx`) has **one** worksheet. A workbook is the file. A worksheet is one sheet. Other spreadsheets: Google Sheets, LibreOffice Calc, Apple Numbers.

- **Formula bar** shows the active cell. The **name box** shows its address (`C5`).
- The active cell has the bold border. Column headings (A, B, C) run across. Row headings (1, 2, 3) run down. Click a heading to select that column or row.
- A cell holds a number, text, or a formula. A formula starts with `=`.
- A function is a built-in formula. `=SUM(B1:B10)` uses SUM. `=1A+2` is invalid: the column letter comes first (`A1`).


| Function      | Result                     |
| ------------- | -------------------------- |
| SUM / AVERAGE | Total / mean               |
| COUNT         | Cells that contain numbers |
| MAX / MIN     | Largest / smallest         |
| LEN           | Characters in a cell       |
| TODAY / NOW   | Date only / date and time  |


- `A4` is relative (both parts shift when copied). `$A$4` is absolute (both stay). `$A4` and `A$4` are mixed: `$` locks the part it sits on.
- Enter confirms. Home goes to the first cell of the row. Shift + Home selects back to the start of the row.
- Charts come from **Insert**. An embedded chart sits on the same sheet as its data. Pie shows parts of one whole. Scatter shows two number series. Parts: chart area, plot area, title, axis title, series, gridlines, legend, data label.


| Action                                            | Shortcut                                 |
| ------------------------------------------------- | ---------------------------------------- |
| Edit cell / Go to / Spelling / Chart on new sheet | F2 / F5 / F7 / F11                       |
| Insert function / Date / Time                     | Shift + F3 / Ctrl + ; / Ctrl + Shift + ; |
| New sheet                                         | Shift + F11 or Alt + Shift + F1          |
| Next / previous sheet                             | Ctrl + Page Down / Ctrl + Page Up        |
| Select column / row                               | Ctrl + Spacebar / Shift + Spacebar       |
| Hide row / column                                 | Ctrl + 9 / Ctrl + 0                      |
| Minimise workbook                                 | Ctrl + F9                                |


Bold, italic, underline, undo, and print match Word.

## Microsoft PowerPoint

A new file is `Presentation1.pptx`. Zoom goes up to **400%**.

- A **design theme** sets shared colours and fonts.
- The **slide master** sets title placement, fonts, and items that repeat on every slide.
- The **handout master** sets the header and footer of printed handouts.
- Header and footer print on every page unless turned off.


| View         | Use                                      |
| ------------ | ---------------------------------------- |
| Normal       | Edit slides                              |
| Slide Sorter | Reorder thumbnails and set transitions   |
| Notes Page   | Speaker notes                            |
| Slide Show   | Full screen. F5 starts it. Esc leaves it |
| Master       | Slide, Handout, and Notes masters        |


Pictures: `.jpg`, `.png`, `.gif`, `.bmp`. Sound: `.wav`, `.mid`. Ctrl + Home / Ctrl + End go to the first / last slide. Ctrl + M inserts a slide. Shift + click selects a continuous run. Ctrl + click selects slides that are apart. Spacebar, Enter, and a click advance the show. Ctrl + P opens Print.

## Microsoft Access

Extension `.accdb`. A database stores related data so it can be added, edited, searched, and deleted.


| Object | Role                           |
| ------ | ------------------------------ |
| Table  | Rows and columns of data       |
| Query  | A question asked of the tables |
| Form   | Screen for entering records    |
| Report | Formatted printout             |


A template is a ready-made database. Query kinds: select, parameter, crosstab, action, and SQL. An action query can make, append, update, or delete.

A field is a column. A record is a row.

 The primary key identifies each record. Each value must be unique, it cannot be blank, and it can use more than one field. A foreign key in another table points at that key. Relationships: one-to-one, one-to-many, many-to-many.


| Data type           | Stores                                     |
| ------------------- | ------------------------------------------ |
| Short Text          | Words. Default size 255                    |
| Long Text           | Long notes                                 |
| Number              | 1, 2, 4, 8, or 16 bytes                    |
| Date/Time, Currency | 8 bytes each                               |
| AutoNumber          | Filled in by Access. Often the primary key |
| Yes/No              | 1 bit                                      |
| Attachment          | Files on a record                          |


Design View builds the table and the key. 

Datasheet View edits the rows.

A validation rule is the condition. Validation text is the failure message.

Required stops a blank field.

F7 checks spelling. 

New queries come from Create.

## Microsoft Outlook

Outlook handles mail, calendar, contacts, and tasks. In an organisation it uses Exchange for shared mail and calendars, and SharePoint for shared lists.