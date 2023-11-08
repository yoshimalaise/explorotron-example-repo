
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

<section>

Even when the content that the student is studying hasn't been curated our extension will try to help the student by showing a list of lenses that are applicable to the file with a rated score of how applicable the lens is, and which PRIMM category it matches.
</section>

<section>

To see this list right-click on any `.js` file and select `Study Lenses > Show recommended Lens`.
</section>

<section>

You can also right-click on any `.js` file and select `Study Lenses > Open in Suggested Lens` to automatically open the file in the highest ranked lens.
</section>

<section>

You can also right-click on any `.js` file and select `Study Lenses > Open in Suggested Lens` to automatically open the file in the highest ranked lens.
</section>

<section>

Finally, right-clicking on any `.js` file and selecting `Study Lenses > Open Suggested Studytour` will open an interactive study tour that will take the learner through multiple applicable lenses to look at the sample file while following a logical difficulty progression.
</section>

---

<section>

# Curated learning

If the repository to be studied has been specifically curated to work with the Explorotron extension that unlocks even more functionality.
</section>

<section>

Teachers can create a curated tour that will take you through multiple files using different lenses that they selected for an optimal learning experience. 
</section>

<section>

Check it out by clicking on the `example-tour.study-tour` file. 
</section>

<section>

Teachers can also can generate `*.study-quiz` files, which are interactive multiple choice questions that can be single or multiple answer questions about snippets of code.
</section>

<section>

Check it out by clicking on the `Sample_Quiz.study-quiz` file.
</section>

---

<section>

# Resources

Click on the Explorotron icon in the left navbar of VS Code to open the commands panel.
</section>

<section>

In this comment panel you will find some useful buttons, such as the `Micromaterials` button, which will open up a page with a curated list of micromaterials that can be found on the web in order to study up on specific topics. New suggestions to be added to the list are always welcome!
</section>

<section>

The `De Nepo` button will open the De Nepo website with useful resources such as the `Web Development Curriculum`.
</section>

<section>

The `Generate Mobile Exercises` button will generate a QR code that can be scanned by the [JSStudyBuddy android application](https://play.google.com/store/apps/details?id=be.ac.vub.wise.jsStudyBuddy) to import exercises based on the current workspace.
</section>

<section>

The `Create Study Tour` and `Create Quiz` buttons can be used to create tours and quizzes such as the ones that you completed earlier. Note that despite their custom file extensions these are simply json files under the hood and can be checked in to the repository and be versioned using git.
</section>

---

<section>

# Any questions?

reach out to me at [ymalaise@vub.be](mailto:ymalaise@vub.be?subject=Explorotron) or find us on [GitHub](https://github.com/yoshimalaise/Explorotron)
</section>