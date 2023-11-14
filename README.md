# adatbaziskezeles



SELECT
    *
FROM
    `kozepiskola`
    INNER JOIN jelentkezes ON kozepiskola.id_kozepiskola = jelentkezes.kozepiskola_id
    INNER JOIN tanulo ON jelentkezes.tanulo_id = tanulo.id_tanulo
   INNER JOIN altalanos_iskola ON tanulo.id_tanulo = altalanos_iskola.id_altalanos_iskola
WHERE
    1
