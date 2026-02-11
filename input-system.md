# Inputs
Los controles en Encrypted están manejados por el componente `PlayerInputSystem`
Este componente en único en todas las escenas y con él podemos usar la suit de inputs que necesitemos en cualquier momento

# Inspect Mode
El modo inspección se activa cuando el jugador tiene un objeto en la mano y presiona la tecla vinculada al modo inspección.
Una vez en el modo inspección se cambiará a la suite de controles correspondiente. Esta suite permite las siguientes acciones:
- Rotación del objeto (PlayerInspector::OnRotationDetected())
- Zoom del objeto (PlayerInspector::OnInspectZoom())
Los parámetros respectivos al modo inspección como pueden ser, la velocidad de rotación o la posición relativa del objeto en modo inspección, se almacenan en el ItemData del objeto en cuestión.
