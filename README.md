<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Fondo azul</title>
    <style>
        body {
            background-color: #0000FF; /* Azul */
        }
    </style>
</head>
<body>
    </body>
</html>
import javax.swing.*;

public class FondoAzul {

    public static void main(String[] args) {
        JFrame ventana = new JFrame("Fondo azul");
        ventana.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        ventana.getContentPane().setBackground(Color.BLUE); // Azul
        ventana.pack();
        ventana.setVisible(true);
    }
}
