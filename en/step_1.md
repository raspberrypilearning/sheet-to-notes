The `picozero` library allows you to enter real musical notes to make tunes to play on your speaker. 

A **letter** is used to represent the musical note and a **number** is used to represent where the note appears on the grand stave (staff). 

![A musical score with a middle C placed on the grand stave.](images/middle-c.png)

For example, the **middle C** (above) is at the centre of the grand stave and uses `c4`.

When you go up the grand stave, the number increases. When you go down the grand stave, the number decreases. 

![A musical score showing the notes going up and down the stave.](images/cdef-cdef.png)

**Representing sharps**

Your musical score might include notes that are **sharps**. These are represented using a `#` symbol. In the example below, the first note is a C sharp. A C sharp is `c#4`. 

![A musical score showing notes that are sharps.](images/sharp-notes.png)

**Representing flats**

Your musical score might include notes that are **flats**. These are **also** represented using a `#` because the library doesn't have a specific code for flats. To turn a flat into a sharp you need to go down the scale. 

+ A **D flat** becomes a **C sharp** or `c#4`
+ An **E flat** becomes a **D sharp** or `d#4`
+ A **G flat** becomes an **F sharp** or `f#4`
+ An **A flat** becomes a **G sharp** or `g#4`

![A musical score showing notes that are flats.](images/flat-notes.png)