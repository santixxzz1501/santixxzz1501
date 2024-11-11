<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mapa Conceptual del Ciclo Menstrual</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f4f9;
        }
        .container {
            width: 80%;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .box {
            background-color: #e0e7ff;
            padding: 15px;
            border-radius: 10px;
            margin: 10px;
            text-align: center;
            max-width: 300px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }
        .box h2 {
            margin: 5px 0;
            color: #4c51bf;
        }
        .box p {
            font-size: 0.9em;
            color: #333;
        }
        .line {
            border-left: 2px solid #4c51bf;
            margin-left: 20px;
            padding-left: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="box">
            <h2>Ciclo Menstrual</h2>
            <p>Comprende el ciclo ovárico y el ciclo uterino, ambos regulados por hormonas bajo un control endocrino.</p>
        </div>

        <div class="line">
            <div class="box">
                <h2>Ciclo Ovárico</h2>
                <p>Incluye la maduración de gametos, el control hormonal y tres fases principales.</p>
                <div class="line">
                    <div class="box">
                        <h3>Maduración</h3>
                        <p>Inicia en el cuarto mes de vida fetal, se detiene al nacer y se reanuda en la pubertad.</p>
                    </div>
                    <div class="box">
                        <h3>Control Hormonal</h3>
                        <p>La GnRH del hipotálamo estimula la liberación de FSH y LH por la hipófisis.</p>
                        <p>FSH promueve el desarrollo folicular y la secreción de estrógenos; LH facilita la ovulación.</p>
                    </div>
                    <div class="box">
                        <h3>Fases del Ciclo Ovárico</h3>
                        <p><strong>Fase Folicular:</strong> La FSH estimula el desarrollo de folículos y la producción de estrógenos.</p>
                        <p><strong>Ovulación:</strong> Un pico de LH y FSH provoca la liberación del ovocito.</p>
                        <p><strong>Fase del Cuerpo Lúteo:</strong> El cuerpo lúteo secreta progesterona; si no hay fecundación, degenera.</p>
                    </div>
                </div>
            </div>

            <div class="box">
                <h2>Ciclo Uterino</h2>
                <p>Compuesto por la estructura del útero y sus tres fases principales.</p>
                <div class="line">
                    <div class="box">
                        <h3>Estructura del Útero</h3>
                        <p><strong>Endometrio:</strong> Capa interna que se engrosa cada mes y se descama sin fecundación.</p>
                        <p><strong>Miometrio:</strong> Capa muscular que permite contracciones en menstruación y parto.</p>
                        <p><strong>Perimetrio:</strong> Capa externa que protege y conecta el útero.</p>
                    </div>
                    <div class="box">
                        <h3>Fases del Ciclo Uterino</h3>
                        <p><strong>Menstruación:</strong> Descama el endometrio y produce sangrado.</p>
                        <p><strong>Fase Proliferativa:</strong> El endometrio se regenera y engrosa para la posible implantación.</p>
                        <p><strong>Fase Secretora:</strong> La progesterona engruesa el endometrio; sin fecundación, se descompone.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
