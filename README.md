# new-.container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: auto auto auto;
  gap: 20px;
}

.header {
  grid-column: 1 / 4; /* Spans all columns */
}

.puzzle {
  grid-column: 1 / 2; /* Place in the first column */
}

.date {
  grid-column: 2 / 4; /* Place in the last two columns */
}
.puzzle-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.puzzle-piece {
  width: 100px;
  height: 100px;
  margin: 5px;
}

.hidden-piece {
  display: none; /* Hides the faulty piece */
}
