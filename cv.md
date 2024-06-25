# Curriculum vitae

## Alexander Borisenko
<img src="https://media.licdn.com/dms/image/D5603AQEe4oLRK66gXA/profile-displayphoto-shrink_800_800/0/1697088579169?e=1724889600&v=beta&t=HSnt5WclZjCbHV-iCwmupuFQp8mc-4dmZfplAlJV_Ig" width="250" height="250">
<br><br>

### Contact information

| Parametr | Value |
| ------------- | ------------- |
| Mobile phone number |  +375(44)7255155<br/> |
| E-mail          |      <sashaborisenko@tut.by><br/> |
| RS-nickname     |      Alexander (@borisfromsouth)<br/> |
| Telegram        |      @boris_from_south<br/> |
| LinkedIn        |      [Ссылка](https://www.linkedin.com/in/alexander-borisenko-203991191)<br/> |
| Github link      |     [Ссылка](https://github.com/borisfromsouth)<br/> |
<br/>

### About myself

I am 24 years old, working and self-improving in the field of programming.
For the last six months I have been developing myself in the direction of the web applications (ASP .Net + Blazor). Every day I try to find time for personal projects and online tutorials in addition to my main job. For more than 3 years I have been working as a programmer at the "Белэлектромонтажналадка" company, supporting and developing the "Уникон" and Configurator desktop application.
<br/><br/>

### Professional skills, languages and technologies

- C# (Framework, Core, Blazor)
- C++
- HTML/CSS
- JS
- React
- Python
- Java (Android)
- Databases (MySQL, SQLite, MongoDB)
- Git (Github, Bitbucket)
- Agile (Scrum)
- BugTracking (Jira, Trelo, Kiten)
<br/><br/>

### Code Example

```
private void _printButton_Click(object sender, EventArgs e)
{
    this.indicators = new List<string>();
    for (int i = 0; i < _indicatorsGridView.Rows.Count; i++)
    {
        indicators.Add(_indicatorsGridView.Rows[i].Cells[1].Value.ToString());
    }
    
    if (_funcButtonsGridView.Visible)
    {
        this.funcButtons = new List<string>();
        for (int i = 0; i < _funcButtonsGridView.Rows.Count; i++)
        {
            this.funcButtons.Add(_funcButtonsGridView.Rows[i].Cells[1].Value.ToString());
        }
    }

    this.printDocument.DefaultPageSettings.Landscape = false;
    printDocument.PrintPage += PrintPageHandler;
    this.printPreviewDialog.Document = this.printDocument;

    ToolStripButton b = new ToolStripButton();
    b.Image = Resources.print;
    b.DisplayStyle = ToolStripItemDisplayStyle.Image;
    b.ImageTransparentColor = Color.Magenta;
    b.Click += SelectPrinterAfterPreview;

    ((ToolStrip)printPreviewDialog.Controls[1]).Items.RemoveAt(0);
    ((ToolStrip)printPreviewDialog.Controls[1]).Items.Insert(0, b);

    this.printPreviewDialog.ShowDialog();
}
```
<br/>

### Job experiense

- 03.2020 - 10.2020   3D Artist (Freelance and Project work(start-up))    Props and buildings modeling and texturing
- 10.2020 - now       ОАО“Белэлектромонтажналадка” C# programmer       Bugfix, Refactor, New features
<br/><br/>

### Education

| Parametr | Value |
| ------------- | ------------- |
| University    |   BSUIR<br/>
| Period        |   2017 - 2021<br/>
| Form of study |   Free<br/>
| Average score |   8,9<br/>
| Faculty       |   Computer-Added Design<br/> 
| Specialty      |  Engineering and psychological support of information technologies<br>
<br/>

### Additional education

- 3d-graphics courses   "Polygon" 2018 - 2019
- English courses       "Streamline" 2019 - 2020, 2022-2023
<br/><br/>

### Languages

|  Parametr | Value |
| ------------- | ------------- |
| Russian   |    Native
| Belarusian |   Native
| English   |  B2 (School, University, Courses (Streamline))
<br/>
