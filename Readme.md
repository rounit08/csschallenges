- Go to https://cssgridgarden.com

Level 1 of 28

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
grid-column-start:3;
}


Level 2 of 28

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#poison {
grid-column-start: 5;
}

Level 3 of 28

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
  grid-column-start: 1;
grid-column-end: 4;
}

Level 4 of 28

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
  grid-column-start: 5;
grid-column-end:2
}

Level 5 of 28 

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
  grid-column-start: 1;
grid-column-end:-2
}

Level 6 of 28

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#poison {
grid-column-start: -3
}

Level 7 of 28

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
  grid-column-start: 2;
grid-column-end: span 2
}

Level 8 of 28

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
  grid-column-start: 1;
grid-column-end: span 5
}

Level 9 of 28


#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
grid-column-start: span 3
  grid-column-end: 6;
}

Level 10 of 28


#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
grid-column: 4/6
}

Level 11 of 28


#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
grid-column:2/5
}

Level 12 of 28


#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
grid-row-start:3
}

Level 13 of 28

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
grid-row:3/6
}

Level 14 of 28

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#poison {
grid-column: 2;
grid-row:5
}

Level 15 of 28

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
grid-column:2/span 5;
grid-row: span 5;
}


Level 16 of 28

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
grid-area:1/2/4/6
}


Level 17 of 28

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water-1 {
  grid-area: 1 / 4 / 6 / 5;
}

#water-2 {
grid-area: 2/3/5/6
}


Level 18 of 28


#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

.water {
  order: 0;
}

#poison {
order:1
}

Level 19 of 28

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

.water {
  order: 0;
}

.poison {
order:-1
}


Level 20 of 28

#garden {
  display: grid;
grid-template-columns: 50%
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
  grid-column: 1;
  grid-row: 1;
}


Level 21 of 28

#garden {
  display: grid;
grid-template-columns: repeat(8, 12.5%);
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
  grid-column: 1;
  grid-row: 1;
}

Level 22 of 28

#garden {
  display: grid;
grid-template-columns:100px 3em 40%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}


Level 23 of 28

#garden {
  display: grid;
grid-template-columns:1fr 5fr
  grid-template-rows: 20% 20% 20% 20% 20%;
}


Level 24 of 28

#garden {
  display: grid;
grid-template-columns: 50px 1fr 1fr 1fr 50px
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
  grid-area: 1 / 1 / 6 / 2;
}

#poison {
  grid-area: 1 / 5 / 6 / 6;
}


Level 25 of 28

#garden {
  display: grid;
grid-template-columns: 75px 1.5fr 1fr
  grid-template-rows: 100%;
}


Level 26 of 28

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
grid-template-rows: 50px 0fr 0fr 0fr
}

#water {
  grid-column: 1 / 6;
  grid-row: 5 / 6;
}


Level 27 of 28

#garden {
  display: grid;
grid-template: 60% / 200px
}

#water {
  grid-column: 1;
  grid-row: 1;
}


Level 28 of 28

#garden {
  display: grid;
grid-template: 1fr 50px/20% 80%
}


Follow [Rounit]/"https://github.com/rounit08"






