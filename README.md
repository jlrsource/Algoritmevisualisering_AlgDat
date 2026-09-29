# Algoritmevisualisering — TDT4120

Interaktiv visualisering av pensumalgoritmene i Algoritmer og datastrukturer (NTNU).
Velg kategori → algoritme, og stegg gjennom CLRS-pseudokoden mens dataene vises steg for steg.

innboforsikring-estimat.vercel.app

**Live** [algoritmevisualisering-alg-dat.vercel.app](https://algoritmevisualisering-alg-dat.vercel.app/)

**Innhold**

- Sortering: INSERTION-SORT, MERGE-SORT, QUICKSORT, HEAPSORT, COUNTING-SORT, RADIX-SORT, BUCKET-SORT, RANDOMIZED-SELECT, SELECT
- Graf: BFS, DFS, TOPOLOGICAL-SORT, SCC (Kosaraju), MST-KRUSKAL, MST-PRIM, BELLMAN-FORD, DAG-SHORTEST-PATHS, DIJKSTRA, FLOYD-WARSHALL, FORD-FULKERSON

Hver algoritme har kjøretider (best/average/worst), invariant og bevisskisse, vanlige eksamensfeller, og steg-for-steg med piltast-navigasjon.

## Kjøre lokalt

Rent statisk — ingen bygging:

```
npx serve .
```

## Filer

- `index.html` — bygget, selvstendig side (deploy denne)
- `Algoritmevisualisering.dc.html` — kilden som redigeres
- `support.js`, `_ds/` — runtime og designsystem som kilden bruker
