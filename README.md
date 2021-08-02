# Learning_Bootstrap
In This Repository, we are trying to learn must follow topics to learn Bootstrap.
## Utilities
For helping developer to make mobile friendly responsive site,
Bootstrap provide dozens of utility classes
1.Background
- If you want to set background then you can use just a single class.
  like- 
   - .bg-primary for blue
   - .bg-dark for dark
- If You want set custom background Just add background-image: var(--bs-gradient);.
To know about how to add background image.You can follow
[Details](https://stackoverflow.com/questions/2504071/how-do-i-combine-a-background-image-and-css3-gradient-on-the-same-element) 
2.Borders
Used to quickly design the style of the border .
two give border write only 
 - border border-1/2....(to give border width) 
 - border-primary/secondary/sucees/light/dark(to give border color)
 - border-0 border-top-0 border-end-0 border-bottom-0 (sybtractive version)
3.colors
To give text color as like as css color.
 - text-primary/success/danger/dark/warning.......    
4.Flex
one of the important topic of bootstrap.Mainly use to make the website layout become responsive easily.I will try discuss few important things regarding this topic.
  1. Flex Behaviour: Flex mainly align the element.You can use d-flex for converting into flex container

5.Sizing & Spacing
 Two types of sizing in bootstrap.
  - depend on parent like-w-25/50/75/100/1uto
  - depend on view-port like-vw-100/vh-100/min-vw-100/min-vh-100 as like
 Spacing Talk about various type of space element like margin,padding,grid gap etc
  - represent margin write m for padding p and for grid gap write gap
  - t-denote top s-dentote strat/left e-denote end/right b-dentote bottom
  - for margin in the top mt-1/2/3/4/5/auto 
  - here value 1 consists in 0.25 to 3 rem default value
6.Text
7.Shadows
 To give different shadow value use shadow for regular and shadow-none/sm/lg important shadow class.Mainly it deonotes box-shadow class.

 various types of Text  class use for various operation
 - text-alignment
    - for alignment text-center/start/end use
    - And also viewport can be set 
      - text-md-center for medium viewport machine text in center 
      - text-sm-center for small viewport machine text in center
      - text-lg-center for large viewport machine text in center
      - text-xxl-center for extra large viewport machine text in center
- Text-wrap
   - use text-wrap class to wrap the text
- Word Break
   - instead of overflow-wrap for wider browser support we use 
      text-break  class
- Text Transform
   - to transform class in upper/lower/capitialize use
     text-uppercase/lowercase/capitialize
- Font Size 
   - to set various font size use fs-1/2/3/4/5/6 class
- Font Weight 
   - to set various font weight use
     fw-/bold/bolder/normal/light/loghter
- Font Style
   - use fst to set italic/normal font style
     fst-italic/normal
- Line Height
   - Line height can be set lh-1/small/base/lg
    small line height
    normal line height 
    large line height
- Reset Color
  - to inherit parent color use text-reset class
- Text Decoration
  - To give underline /line through the line/without any decoration
    - text-decoration-underline for giving underline
    - text-decoration-line-through fot giving line through the line
    - text-decoration-none without any decoration
    
8.Display
9.float
10.Interacctions
11.Overflow
12.Visibility

# Panda Commerce Website
 practicing website using bootstrap.

 # How to create multiple columna and rows
 You can create multiple column simultaneously.
 Create one column then create row inside the column.Also create multiple column inside the nested row.
 .row

 .col-6 |.col-6
 -------|----------------------
 .row  | .row.col-5 |.row.col-6
-------|------------|----------
