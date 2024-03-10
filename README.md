when green flag clicked
forever
    if <all dots collected?> then
        broadcast win
    if <Pac-Man touches ghost?> then
        broadcast lose
    // Additional game logic can go here

when I receive win
    // Show win message or animation

when I receive lose
    // Show lose message or animation

when arrow key [up v] pressed
    // Move Pac-Man up

when arrow key [down v] pressed
    // Move Pac-Man down

when arrow key [left v] pressed
    // Move Pac-Man left

when arrow key [right v] pressed
    // Move Pac-Man right
