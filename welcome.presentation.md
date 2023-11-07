
### Welcome to the Explortron Example Repository!

This presentation will take you through some of the key features provided by the extension, so let's get started!

---

<section>
A first feature is the ability to show presentations, directly in VS Code right where your students are. 
</section>

<section>

Presentations are simply markdown files that are rendered as interactive presentations using [`markdown.js`](https://revealjs.com).

</section>

<section>

This has a couple of advantages:
</section>



<section>

- No special software is needed to edit the presentations
</section>


<section>

- The presentations can live directly in the repository and can even make use of source control so your presentations and code content are always in sync.
</section>

<section>

- The markdown files still make sense as plain text files even if the student does not have presentation software installed on their computer.

</section>


---

<section>

## Study Lenses

Are the second main feature of the explorotron extension
</section>

<section>

The idea behind a study lens is simple, take a source file and render it as an interactive exercise.
</section>

<section>

The main motivation behind our lenses are the insights gained from Computing Education Research such as the theory behind [PRIMM](https://primmportal.com).

</section>

<section>

The reality is however that creating quality material that covers all these steps requires a huge time investment from teachers.

</section>

<section>

This is where our lenses come in, simply right click any `*.js` file in the VS Code file explorer and you'l see a new menu item called `study lenses`. 

</section>

<section>

Hovering over that option will open up a new context menu with some actions on top, followed by the available study lenses at the bottom.

</section>

<section>
Currently the Explorotron extension supports the following 10 lenses.

<div style="{display: flex, flex-direction: row}">
    <ul>
        <li>Annotate</li>
        <li>Arguments Picker</li>
        <li>Blanks</li>
        <li>Code Questions</li>
        <li>Comment Slots</li>
    </ul>
    <ul>
        <li>Flowchart</li>
        <li>Parsons</li>
        <li>Pick Flowchart</li>
        <li>Pseudify</li>
        <li>Trace  </li>
    </ul>  
</div>       
</section>

<section>

Feel free to try some of the lenses out for yourself by right clicking any of the `.js files` in the sorting algorithms directory!
</section>

<section>

The choice to work with regular js source files instead of a custom exercise source document was made deliberately as it *prevents any vendor lock-in* and enables our students to take their learning tools with them, *regardless of where they get their content*
</section>


---

<section>

### Guided learning

</section>

<section>

While the lenses are great for offering students the flexibility of studying content they want to learn how they want to learn it, it can lack a bit of direction if the student doesn't know a good way to approach a topic. Sometimes a little guidance is benificial.
</section>