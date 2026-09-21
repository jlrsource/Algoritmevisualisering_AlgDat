# Algoritmevisualisering — TDT4120

Interaktiv visualisering av pensumalgoritmene i Algoritmer og datastrukturer (NTNU).
Velg kategori → algoritme, og stegg gjennom CLRS-pseudokoden mens dataene vises steg for steg.

**Innhold**

- Sortering: INSERTION-SORT, MERGE-SORT, QUICKSORT, COUNTING-SORT, RADIX-SORT, BUCKET-SORT, RANDOMIZED-SELECT, SELECT
- Graf: BFS, DFS, TOPOLOGICAL-SORT, SCC (Kosaraju), MST-KRUSKAL, MST-PRIM, BELLMAN-FORD, DAG-SHORTEST-PATHS, DIJKSTRA, FLOYD-WARSHALL, FORD-FULKERSON

Hver algoritme har kjøretider (best/average/worst), invariant og bevisskisse, vanlige eksamensfeller, og steg-for-steg med piltast-navigasjon.

## Kjøre lokalt

Rent statisk — ingen bygging:

```
npx serve .
```

## Deploy til Vercel

`index.html` er en komplett, selvstendig side (all CSS, JS og fonter er inlinet).

```
npm i -g vercel
vercel
```

Eller koble repoet i Vercel-dashbordet: Framework preset **Other**, ingen build command, output directory `.`.

## Filer

- `index.html` — bygget, selvstendig side (deploy denne)
- `Algoritmevisualisering.dc.html` — kilden som redigeres
- `support.js`, `_ds/` — runtime og designsystem som kilden bruker
