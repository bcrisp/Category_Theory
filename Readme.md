
#Category Theory for Philosophy Majors

### Modeling &lambda;-calculus

## Equivalent notions of computation
- Turing Machine can use a read/write and on a tape to perform any computation
- Recursive functions can be used to perform any computation
- Lambda calculus can be used to perform any computation


Turing &equiv; Recursive &equiv; Lambda Calculus

##What are abstractions?

Basis behind map and filter. Parametricity.

Something between "map is kind of like, you don't have to put in the variable, and it just works like magic".


## Categories

- Collection of objects with arrows between them
- Equivalently, a directed graph

Examples: 

- A singly-linked list is a category with objects as list items and morphisms linking them together

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
<mtable rowspacing="5pt" columnspacing="5pt">
  <mtr>
    <mtd>
      <mi>Object</mi>
      <mpadded height="8.5pt" depth="2pt" />
    </mtd>
    <mtd>
      <mover>
        <mo minsize="2.75em">&#x2192;</mo>
        <mpadded width="+0.611em" lspace="0.333em" voffset=".1em">
          <mrow class="MJX-TeXAtom-ORD">
            <mi>pointer</mi>
          </mrow>
        </mpadded>
      </mover>
    </mtd>
    <mtd>
      <mi>Object</mi>
    </mtd>
    <mtd>
      <mover>
        <mo minsize="2.75em">&#x2192;</mo>
        <mpadded width="+0.611em" lspace="0.333em" voffset=".1em">
          <mrow class="MJX-TeXAtom-ORD">
            <mi>pointer</mi>
          </mrow>
        </mpadded>
      </mover>
    </mtd>
    <mtd>
    <mi>Object</mi>
    </mtd>
  </mtr>
</mtable>
</math>


- A graph has vertices as objects and edges as morphisms

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
<mtable rowspacing="5pt" columnspacing="5pt">
  <mtr>
    <mtd>
      <mi>A</mi>
      <mpadded height="8.5pt" depth="2pt" />
    </mtd>
    <mtd>
      <mover>
        <mo minsize="2.75em">&#x2192;</mo>
        <mpadded width="+1.611em" lspace="0.333em" voffset=".1em">
          <mrow class="MJX-TeXAtom-ORD">
          </mrow>
        </mpadded>
      </mover>
    </mtd>
    <mtd>
      <mi>C</mi>
    </mtd>
  </mtr>
  <mtr>
    <mtd>
      <mo lspace="0" rspace="0" symmetric="true" minsize="1.75em">&#x2193;</mo>
    <mtd />
  </mtr>
  <mtr>
    <mtd>

      <mi>B</mi>
      <mpadded height="8.5pt" depth="2pt" />
       
    </mtd>

    </mtd>
  </mtr>
</mtable>
</math>


- &lambda;-calculus has objects as terms and morphisms as &beta;-reductions

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
<mtable rowspacing="5pt" columnspacing="5pt">
  <mtr>
    <mtd>
      <mi>7</mi>
        <mo stretchy="false">&mapsto;<!-- → --></mo>      <mpadded height="8.5pt" depth="2pt" />
    </mtd>
    <mtd>
    (&lambda;x.x&sdot;6)
    </mtd>
    <mtd>
<mo>&mapsto;   </mo> </mtd>
    <mtd>
<mo>42</mo>
    </mtd>
  </mtr>
</mtable>
</math>

### Objects

### Morphisms

### Hom-sets

Must respect composition: g &omicron; f= 


hom(a, b) x hom(b, c) -> hom(a, c)

This should make sense. This is "normal", we're just trying to prevent pathological functions here

Category company process

Let arrows indicate flow
Let objects indicate our objects

### Functors

## Parametricity


## Currying



##F-Algebras



Hom functors

For all objects A, B in C, let's define two functors to the category of sets

Hom(A, -) maps each object X in C to the set of morphisms Hom(A, X), and maps each morphism f: X -> Y to the function Hom(A, f): Hom(A, X) -> Hom(A, Y)

, so this becomes a set of morphisms from A -> X

a set of functions
