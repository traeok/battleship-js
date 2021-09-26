# bship
A minimalistic Battleship clone in HTML, styled by CSS and powered by JS


- Each player has the right to 3 pieces: an aircraft carrier, battleship, and submarine.
  - Aircraft carriers are 5 spaces long, battleships are 4 spaces long, and submarines are 3 spaces long. 
- To place each item, they must be input in the following Regex format:
```javascript
/([ABSabs]{1})[:]?[\(]?([a-jA-J]{1}[1-9]{1}[0]?)-([a-jA-J]{1}[1-9]{1}[0]?)[\)]?/
```

- To break this down: **A/B/S** to designate the piece, followed by a colon and its coordinates
- Coordinates can be placed in parentheses or immediately after the colon
- Separate each piece's information with a semi-colon
- **Example input:** A(A1-A5); B(B1-B4); S(C1-C3)
  - Would create an aircraft carrier from A1-A5, a battleship from B1-B4, and a submarine from C1-C3

This project was created in response to a set of requirements. It is all my own and I own the rights to this work (in simple terms, you can't use this code.)
