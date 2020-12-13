---

#### valores Hard-coded/absolute
```css
 h1 {
   font-size: 24px;
   line-height: 32px;
   }
```

* Las alturas de las líneas siempre deben establecerse en valores relativos para que sean más tolerantes y flexibles.
* Si alguna vez cambia el tamaño de fuente de un h1 (párrafo o lo que sea), querremos seguir mantenindo esa proporción

---

### !important de forma proactiva 😁, no reactiva 😖

* !important está bien. Está bien y es una herramienta importante.
* Sin embargo, ! Important solo debe utilizarse en determinadas circunstancias.
* !important sólo debe usarse de forma proactiva, no reactiva.

* hay momentos en los que sabes que siempre, siempre querrás que un estilo tenga prioridad, y lo sabrás desde el principio.

```css
.error-text {
color: #cc0000 !important;
}
```
