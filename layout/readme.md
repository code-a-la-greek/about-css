# Layout

Στα παρακάτω βίντεο εξετάζουμε τρόπους για να αλλάξουμε το layout της σελίδας.

## Position

[Εδώ](https://youtu.be/A_gnxwoovE8) αναλύουμε τα πλεονεκτήματα και μειονεκτήματα της ιδιότητας `position`

## Flexbox

[Εδώ](https://youtu.be/a72nYJdCzNI) αναλύουμε το `flexbox` και τις ιδιότητές του.

### Flexbox Properties:

**Parent-element**

- display:flex
- flex-direction: row(default)/column/row-reverse/column-reverse
- flex-wrap: nowrap/wrap/wrap-reverse
- justify-content:
  - start
  - end
  - stretch
  - center
  - space-around
  - space-between
  - space-evenly
- align-items:
  - start
  - end
  - stretch
  - center
- gap

**Child-element**

- flex

## Grid

[Εδώ](https://youtu.be/kRXqiUq4HME) αναλύουμε το `Grid` και τις ιδιότητές του.

### Grid Properties:

**Parent-element**

- display:flex
- gap
- grid-auto-flow: row/column
- grid-template-columns: 1fr 1fr 1fr 1fr;
- grid-template-columns: repeat(4,1fr);
- grid-template-columns:
  minmax(150px,1fr) minmax(200px,1.5fr);
- grid-template-columns:
  repeat(auto-fit,minmax(150px,1fr));
- grid-template-columns:
  repeat(auto-fill,minmax(150px,1fr));

**Child-element**

- grid-column: αριθμός της πρώτης στήλης/αριθμός της τελευταίας στήλης
- grid-row: αριθμός της σειράς που επιθμούμε
- grid-row: αριθμός της πρώτης σειράς/αριθμός της τελευταίας σειράς
- grid-column/row: span 2
  ο αριθμός δηλώνει πόσες στήλες ή σειρές το στοιχείο μας θα επεκτείνεται
