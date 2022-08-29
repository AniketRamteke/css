# All About Box Model

Total height of an element = border top height + padding top + content height + padding bottom + border bottom height.

#### and

Total width of an element = border width left + padding left + content width + padding right + border width right.

## PADDING

Padding can be defined seperatel on whichever side needed:
padding-top, padding-left etc.

### OR

padding : ZZpx YYpx; (top-bottom and left-right resp.)
padding: AApx BBpx CCpx DDpx; (top -> right -> bottom -> left direction);

## MARGIN

<!-- Collapsing Margins -->

if margin-bottom and margin-top of adjacent elements are defined,
then the total margin between them is whichever is greater between them.

## DIMENSIONS (Width and Height)

defining height and width results only in changing the content's dimension and does not effect on padding or margin.
