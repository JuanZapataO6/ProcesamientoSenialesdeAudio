# ProcesamientoSenialesdeAudio
 Proyecto I: Procesamiento Señales de Audio Implementar un sistema de procesamiento de señales de audio con las siguientes especificaciones generales: A. Ambiente de programación: Matlab, Python, Mathematica, C, C++ B. Señal de entrada análoga: Voz y música C. Adquisición: Micrófono y Tarjeta de audio del PC. D. Funciones de Procesamiento - 𝐶𝑜𝑛𝑣𝑜𝑙𝑢𝑐𝑖ó𝑛 𝑠𝑖𝑠𝑡𝑒𝑚𝑎 𝐹𝐼𝑅: 𝑦(𝑛) = ∑ 𝑥(𝑛 − 𝑘)ℎ(𝑘) 𝑛 𝑘=0 - 𝐸𝑐𝑢𝑎𝑐𝑖ó𝑛 𝑑𝑒 𝑑𝑖𝑓𝑒𝑟𝑒𝑛𝑐𝑖𝑎 𝑆𝑖𝑠𝑡𝑒𝑚𝑎 𝐼𝐼𝑅: 𝑦(𝑛) = − ∑ 𝑎𝑘 𝑎0 𝑦(𝑛 − 𝑘) 𝑁 𝑘=1 + ∑ 𝑏𝑘 𝑎0 𝑥(𝑛 − 𝑘) 𝑀 𝑘=0 - El programa debe permitir introducir los parámetros de los sistemas [ℎ(𝑛), 𝑎𝑘, 𝑏𝑘 ] a través de una ventana de diálogo. - Debe implementar funciones propias para calcular las ecuaciones de convolución y ecuaciones de diferencia. NO se acepta el uso de funciones de Matlab para tal fin. E. Visualización en el PC (Adquisición en Tiempo NO Real) - Señales digitales de entrada y salida en tiempo real. - Valores de amplitudes y tiempo en las gráficas. F. Máximo número de estudiantes por grupo: 4 G. La interfaz de usuario debe permitir las siguientes operaciones: - Seleccionar la señal de entrada de un archivo - Reproducir señales de audio - Grabar archivos de audio - Generar función chirp con parámetros ajustables por el usuario - Seleccionar el filtro a aplicar por convolución y ecuaciones de diferencia (No usar la funciones filter y conv o equivalentes en el lenguaje utilizado ) o Utilizar una señal chirp para prueba de los filtros o Utilizar señales de audio - Operaciones adicionales: - Sumar y multiplicar dos señales de audio - Reproducir de forma inversa el audio - Convertir una señal estereofónica (un solo canal) a monofónica (dos canales) y viceversa. - Conformar una señal estéreo a partir de dos señales monofónicas - Ajustar el volumen del audio o Amplitud constante o Amplitud cambiando linealmente (creciente y decreciente) - Verificación y Cambio de la frecuencia de muestreo antes de realizar operaciones entre audios o Opción 1: Usar dos funciones separadas de la librería del lenguaje seleccionado. Por ejemplo Decimate e Interp de Matlab) o Opción 2: Usar sola la función de Matlab: interp1