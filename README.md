<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Línea del Tiempo F1</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-image: url('images/tela.jpg');   
      background-size: cover;
      background-repeat: no-repeat;
      background-attachment: fixed; 
      background-position: center;
      color: #f1f1f1;
    }

    h1 {
      text-align: center;
      color: #e10600;
      padding: 1em 0;
    }

    .timeline {
      position: relative;
      max-width: 900px;
      margin: auto;
      padding: 20px 0;
    }

    .timeline::after {
      content: '';
      position: absolute;
      width: 4px;
      background-color: #e10600;
      top: 0;
      bottom: 0;
      left: 53%;
      margin-left: -2px;
    }

    .event {
      padding: 20px 30px;
      position: relative;
      width: 50%;
    }

    .event::after {
      content: '';
      position: absolute;
      width: 20px;
      height: 20px;
      right: -10px;
      background-color: #e10600;
      border: 3px solid #fff;
      top: 30px;
      border-radius: 50%;
      z-index: 1;
    }

    .left {
      left: -15px;
    }

    .right {
      left: 50%;
    }

    .right::after {
      left: -10px;
    }

    .event-content {
      background-color: #222;
      padding: 20px;
      border-radius: 8px;
      position: relative;
      box-shadow: 0 0 10px rgba(255, 0, 0, 0.2);
      display: flex;
      flex-direction: row-reverse; /* imagen a la derecha */
      align-items: center;
      gap: 20px;
    }

    .event-content img {
      width: 160px;
      border-radius: 8px;
      border: 2px solid #e10600;
      flex-shrink: 0;
    }

    .img-grande {
      width: 200px; /* más grande */
    }

    @media screen and (max-width: 768px) {
      .event {
        width: 100%;
        left: 0 !important;
      }

      .event::after {
        left: calc(50% - 10px) !important;
      }

      .event-content {
        flex-direction: column;
        align-items: flex-start;
      }

      .event-content img {
        width: 100%;
      }
    }
  </style>
</head>
<body>

  <h1>¿Cómo nos conocimos?</h1>
  <div class="timeline">

    <div class="event left">
      <div class="event-content">
        <img src="images/alianza.jpeg" alt="Reyes de alianza" />
        <div>
          <h3>Q1 - Alianzas</h3>
          <p>13/03/2025. Aquí fue donde nos conocimos, y donde me gané todo tu odio y desprecio.  
          A pesar de todo, me quedé con una excelente impresión tuya: dicharachera, buena onda, agradable.  
          Se pasó súper, ¡además se ganó en el baile! ¡CTM VIVA CHILE MRD!</p>
        </div>
      </div>
    </div>

    <div class="event right">
      <div class="event-content">
        <img src="images/carritos.jpeg" alt="FoodTrucks">
        <div>
          <h3>Q2 - FoodTrucks</h3>
          <p>24/03/2025. Mientras los demas hablan lo suyo, nosotros nos pusimos de hablar de nuestros propios temas, como lo mucho que queríamos que alguien nos quisiera de verdad.  
          Y lo mucho que nos gustaban los autitos: Fast & Furious, Paul Walker, Hot Wheels...  
          Aquel día comenzamos a hablar por IG, y no paramos más.</p>
        </div>
      </div>
    </div>

    <div class="event left">
      <div class="event-content">
        <img src="images/chue.jpeg" alt="Viaje a Curanilahue">
        <div>
          <h3>Q3 - Viaje a Curanilahue</h3>
          <p>17/04/2025. Fue el día que viajamos a Curanilahue juntos, donde estuvimos todo el viaje conversando.  
          Ahí fue donde me di cuenta y confirmé que me estabas empezando a gustar.  
          Recuerdo que no quería que llegara el bus, porque no me quería ir, y cuando llegó, no me fui hasta que vi que el bus partió.  
          Ese día quedé lleno de dudas, sentí cosas de chavito, quedé flechado con la foto que te saqué, esos ojos, fua directamente caí.  
          Esa misma semana fue cuando sucedió el “Nosotros pa cuando”.</p>
        </div>
      </div>
    </div>

    <div class="event right">
      <div class="event-content">
        <img src="images/firma.jpeg" alt="La gran firma" class="img-grande">
        <div>
          <h3>Primera Carrera - El comienzo</h3>
          <p>24/04/2025. Luego, de unos cuantos días, donde las cosas estaban raras, pasábamos más tiempo juntos, había más contacto físico, y en general, poco a poco nos íbamos siendo más unidos. El día 23 de Abril, decido, que es hora de hablarlo, por un lado, sentía que todo era mutuo, que había más que simple amistad, y a pesar de que, estuviste todo el día tratando de esquivar el tema, finalmente, en la pasarela, llego el momento, lo conversamos muy poco en verdad, quedamos en nada. Pero para mi suerte, nos íbamos ambos por el mismo lado, y al final de la pasarela, lo volvimos a hablar, estabas totalmente negada, mientras que yo… Loco por que dejaras esos miedos de lado, y te animaras, no me dijiste nada, pero horas más tardes, me enviarías la “Sentencia provisoria”  la cual, firme sin dudar, y ha sido de las mejores decisiones que he tomado este año</p>
        </div>
      </div>
    </div>

    <div class="event left">
      <div class="event-content">
        <img src="images/pelis.jpeg" alt="Noche de pelis">
        <div>
          <h3>Segunda Carrera - Primera noche de pelis</h3>
          <p>25/04/2025. Justamente al día siguiente, teníamos un carrete en tu casa donde, claro, si quería estar, me tenía que quedar,  
            y aunque lo encontré como muy patudo, no me arrepiento de nada.  
            No solo pasamos casi todo el día juntos, además, tuvimos nuestra primera noche de pelis, donde vimos “La princesa y el sapo”  
            y “Cars” juntos, además de darnos nuestro primer beso de chavos enamorados.  
            Fue un día maravilloso, nos acostamos re tarde, la pasamos bonito, en lo personal un día mágico y perfecto.</p>
        </div>
      </div>
    </div>

    <div class="event right">
      <div class="event-content">
        <img src="images/paro.jpeg" alt="Nuestro primer paro" class="img-grande">
        <div>
          <h3>Tercera Carrera - Nuestro primer paro</h3>
          <p>13/05/2025. Entre las cosas que nos ha tocado pasar este año, tenemos el paro, tiempo en el cual, aprovechamos para estudiar, y juntarnos a ver películas. Compramos cositas auspiciada por la juna, y esa noche, me quede en tu casita.</p>
        </div>
      </div>
    </div>

    <div class="event left">
      <div class="event-content">
        <img src="images/matrimonio.jpeg" alt="Pedida de matrimonio">
        <div>  
            <h3>Cuarta Carrera - Primera pedida de matrimonio</h3>
          <p>04/06/2025. Aquel día te regale el primero (espero que de muchos) completo, y creo que nunca he visto a una persona tan feliz con un completo en la mano, aparte de verte super tierna en la mano, se considero como la primera pedida de matrimonio dentro de la relación.   </p>
        </div>
      </div>
    </div>

    <div class="event right">
      <div class="event-content">
        <img src="images/especial.jpeg" alt="Día especial">
        <div>
          <h3>Quinta Carrera - Día especial</h3>
          <p>10/06/2025. Aquel día nos quedamos tiempo demás en la U, no nos queríamos ir, pero lamentablemente un señor vive medio lejitos, y después queda botado. Ese día nos sacamos fotos, grabamos videítos, conversamos, reímos mucho, y aunque al llegar a la casa me retaron, no me importo, porque estaba contigo, y por estar contigo, hago lo que haga falta, y me aguanto los retos que sean necesarios.    </p>
        </div>
      </div>
    </div>

    <div class="event left">
      <div class="event-content">
        <img src="images/panqueques.jpeg" alt="Panqueques">
        <div>  
            <h3>Sexta Carrera - Panqueques</h3>
          <p>19/06/2025.
De milagro, ese día llegue temprano a la U, de hecho, llegamos juntos a las 7, y ese día me regalaste panqueques y además una cartita. Mis ánimos no andaban al 100, me estaba planteando todo, pero ese gesto, me alegro la semana, estaban muy ricos, además, de que nadie nunca me había regalado panqueques. En ese momento, me empecé a dar cuenta que no solo te quería y adoraba, sino que, era más que eso, el te quiero se me empezaba a quedar corto.   </p>
        </div>
      </div>
    </div>

    <div class="event right">
      <div class="event-content">
        <img src="images/cita.jpeg" alt="Primera cita">
        <div>
          <h3>Septima Carrera - Nuestra primera cita</h3>
          <p>24/06/2025. Fue nuestra primera cita oficial, el poder salir juntos afuera, fuimos a una cafetería, luego recorrimos la udec y me enseñaste la laguna de los patos, donde, debo de admitir, tenia muchas ganas de robarme un pato y entregártelo, como muestra de mi amor, que en ese momento, ya sabia que te amaba, pero me daba miedo decirlo, aunque estuve a punto, no me atreví por miedo. Casualmente nos pusimos de acuerdo en regalarnos las pulseras, además de regalarte a Sally, y así por fin, tener a McQueen y Sally juntitos. </p>
        </div>
      </div>
    </div>

    <div class="event left">
      <div class="event-content">
        <img src="images/teamo.jpeg" alt="Primer Te amo">
        <div>  
            <h3>Octava Carrera - Primer "Te amo"</h3>
          <p>26/06/2025. Ese día fuimos a ver la nueva película de F1, es cosa de recordar y sonreír de una manera impresionante, no solo fue el hecho, de poder ver una película en el cine, sino, además, de con quien estaba viendo esa película. La película 10/10, espectacular, pero el hecho de que estuvieras ahí lo marco y cambio todo, en ese momento, gracias a la película, me di cuenta de que necesitaba decirte, lo que sentía, que no solo te quería, si no que ya te amaba, te amaba como a nadie he amado en mi vida. Además, el cómo nos emocionamos, hasta el punto de casi levantarnos de la butaca, nanana, una cosa bárbara. </p>
        </div>
      </div>
    </div>

    <div class="event right">
      <div class="event-content">
        <img src="images/semestre.jpeg" alt="Kiuut">
        <div>    
          <h3>Novena Carrera - Termino de semestre</h3>
          <p>09/07/2025. A pesar de que ya habías salido de clases y yo estaba dando mi ultimo certamen, me fuiste a ver a la U igual, fuimos al Mall, vitrineamos por aquí y por allá, conversamos, reímos, lloramos, y al igual que siempre, cuando era hora de irnos, ninguno de los dos quería irse, pero esta vez era diferente, porque no sabíamos cuando nos volveríamos a ver, porque comenzaban vacaciones, a pesar de eso, te prometí, que si o si nos íbamos a ver para nuestra fecha, sin falta, estaríamos juntos el 24. </p>
        </div>
      </div>
    </div>

    <div class="event left">
      <div class="event-content">
	<img src="images/canete.jpeg" alt="tirado">
        <div>
        <h3>Decima Carrera - Atrapado en Cañete </h3>
        <p>15/07/2025. Ese día te fui a verte a Cañete, fuimos al Mall Chino y compramos dulces para probar, conocí tu liceo, a nuestro hijo, y también a tus padres, aunque no estaba en los planes, ALGUIEN quedo tirado en cañete. A pesar de eso, estuvimos toda la tarde juntos, disfrute mucho estar contigo, además de estar muy agradecido de que me hayas presentado y mostrado una parte más intimida de ti, como lo son algunas amistades, y tu ex liceo, además, de estar muy agradecido por la amabilidad de tu madre. Por ti iría hasta la luna si es necesario con tal de verte. </p>
      </div>
      </div>
    </div>

    <div class="event right">
      <div class="event-content">
	<img src="images/novio.jpeg" alt="novios">
        <div>
        <h3>Onceava Carrera - Novios Oficiales</h3>
        <p>24/07/2025. Después de estar bromeando, que si octubre, que si noviembre, diciembre o enero, obviamente, nunca esperaría tanto. Ya lo tenía en mente desde junio, y aunque, por desgracia no salió como quería, curiosamente, al igual, que la primera vez que salimos y anduvimos de la mano, fue en un Mall, pues, la propuesta de novios oficial fue en un Mall. Iba muerto de nervios, quería que fuera especial, tal como lo tenia pensado, pero no salió así, y aunque me duele que no haya salido según mis planes, al final del día estaba muy contento porque, ya éramos novios oficiales, ya era tu novio oficial. </p>
      </div>
      </div>
    </div>

    <div class="event left">
      <div class="event-content">
	<div>
        <h3>Doceava Carrera - El presente</h3>
        <p>01/08/2025. Y bueno, en este día de la novia, claramente no puedes ser espectadora, este es el pequeño gesto que te tenia preparado y en el cual trabaje. Lo siento si no es la gran cosa, me hubiera encantado haberlo podido pasar contigo en persona. Espero sea el primero de muchos, te amo, te amo como no te puedes hacer una idea, y aunque a veces me cueste demostrarlo, no quiero que nunca lo pongas en dudas. Te elijo a ti, una y mil veces, por sobre todo los motivos, cada día te amo más, y cada día me gustas más también, sé que no la has pasado del todo bien, pero sabes que estoy para ti, siempre. Sin más mucho que agregar, te amo, feliz día para la novia más hermosa y maravillosa del mundo, te amo millones, te mando un beso y un abrazo enorme. MUA </p>
      </div>
    </div>

      </div>
</body>
</html>
