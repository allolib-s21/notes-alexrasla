# notes-alexrasla
- These modified files add both GUI and backend funtionality for a looping "pedal". The looping checkbox is found under the Event Sequencer tab and allows you to loop your sequence infinitely. It was implemented by registering a callback function at the end of the sequence. The callback function simply calls playSequence again, which enables the infinite looping feature.
