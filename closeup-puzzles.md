# Closeup Puzzles
Los controles en Encrypted están manejados por el componente `PlayerInputSystem`
Este componente en único en todas las escenas y con él podemos usar la suit de inputs que necesitemos en cualquier momento

Los puzles Closeup son los puzles donde la cámara se centra en el puzle y los controles se centran en el puzle propio.
Para ello, ocurre lo siguiente:
- Heredan de `ICloseupPuzleController`
- Se utiliza el Input de Locomotion a Closeup
- Se cambia la cámara para centrarse en el puzle


## Gear Puzzle
Este puzle consiste en colocar los engranajes/gears en su sitio/Spot correspondiente
La implementación de su controlador es `GearPuzleController`


## Keyboard Puzzle
Este puzle consiste en un teclado numérico donde introducir una contraseña
La implementación de su controlador es `KeyboardPuzleController`


# UML Diagram
Los diagramas sobre la implementación actual de los componentes de los puzles Closeup son los siguientes:
![UML diagram CloseupPuzzle](Media/UML_diagram_CloseupPuzle.png)