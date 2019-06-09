# emulator-EC1
El emulador de la máquina USC-1 necesita para su correcto funcionamiento la implementación de tres fases: la fase de fetch, la fase de decodificación y la fase de ejecución. En la fase de fetch lo que tiene que hacer el emulador es ocuparse de cargar la siguiente instrucción a ejecutar, indicada por el contador de programa, en el registro de instrucción y dejar listo el EPC para que apunte a la siguiente instrucción. Lo que se hace en la fase de decodificación es transcribir la instrucción que se va a ejecutar para averiguar de qué tipo es y qué es lo que se tiene que hacer para que se lleve a cabo. En la fase de ejecución el emulador realiza los procesos necesarios para imitar el comportamiento que tendría que tener la máquina original (USC-1). 
