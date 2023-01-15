### Learnt:

#### React:

1. lazy initial state
2. findCurrentNote()
   ```
   function findCurrentNote() {
       // return the note that match id
       return (
       notes.find((note) => {
           return note.id === currentNoteId;
       }) || notes[0]
       );
   }
   ```
3. `event.stopPropagation();`
