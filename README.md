# Catálogo de criaturas (motor-rs)

33 personajes (criatura + skin), cada uno con su GIF de portada y un GIF por animación y por dirección.

## Estructura

```
catalogo.json                         índice para la app (id, criatura, skin, portada, animaciones → 8 GIFs)
gifs/<criatura>/<personaje>.gif       portada: caminar, vista 3/4 (SE), zoom 6x
gifs/<criatura>/<personaje>/<animacion>/<DIR>.gif   zoom 4x; DIR = S SE E NE N NW W SW
```

Animaciones: agachar, blandir, caminar, caminar_lpc, combo, correr, desenvainar, golpear, neutra, quieto, saltar, zombi_caminar, zombi_correr, zombi_golpear, zombi_quieto, zombi_saltar (las `zombi_*` solo existen para el zombi y reemplazan a las genéricas).

## Criaturas y skins

| Criatura | Skins |
|---|---|
| ciclope | [ciclope_bronce](gifs/ciclope/ciclope_bronce.gif), [ciclope_pantano](gifs/ciclope/ciclope_pantano.gif), [ciclope_piedra](gifs/ciclope/ciclope_piedra.gif) |
| elfo | [elfo_bosque](gifs/elfo/elfo_bosque.gif), [elfo_dorado](gifs/elfo/elfo_dorado.gif), [elfo_oscuro](gifs/elfo/elfo_oscuro.gif) |
| enano | [enano_bronce](gifs/enano/enano_bronce.gif), [enano_hierro](gifs/enano/enano_hierro.gif), [enano_mina](gifs/enano/enano_mina.gif) |
| esqueleto | [esqueleto_ceniza](gifs/esqueleto/esqueleto_ceniza.gif), [esqueleto_hueso](gifs/esqueleto/esqueleto_hueso.gif), [esqueleto_oxidado](gifs/esqueleto/esqueleto_oxidado.gif) |
| gnomo | [gnomo](gifs/gnomo/gnomo.gif) |
| goblin | [goblin](gifs/goblin/goblin.gif) |
| golem | [golem_arenisca](gifs/golem/golem_arenisca.gif), [golem_basalto](gifs/golem/golem_basalto.gif), [golem_piedra](gifs/golem/golem_piedra.gif) |
| humano | [caballero](gifs/humano/caballero.gif), [hechicera](gifs/humano/hechicera.gif), [vampira](gifs/humano/vampira.gif) |
| humanoide | [humanoide](gifs/humanoide/humanoide.gif) |
| ogro | [ogro_gris](gifs/ogro/ogro_gris.gif), [ogro_montana](gifs/ogro/ogro_montana.gif), [ogro_pantano](gifs/ogro/ogro_pantano.gif) |
| orco | [orco_caudillo](gifs/orco/orco_caudillo.gif), [orco_cenizas](gifs/orco/orco_cenizas.gif), [orco_desierto](gifs/orco/orco_desierto.gif) |
| troll | [troll_cueva](gifs/troll/troll_cueva.gif), [troll_musgo](gifs/troll/troll_musgo.gif), [troll_piedra](gifs/troll/troll_piedra.gif) |
| zombi | [zombi_palido](gifs/zombi/zombi_palido.gif), [zombi_podrido](gifs/zombi/zombi_podrido.gif), [zombi_verde](gifs/zombi/zombi_verde.gif) |

Generado con `motor-rs gif <personaje> --animacion <anim> --dir <DIR> --zoom 4`.
