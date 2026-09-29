# Algoritmevisualisering — TDT4120

Interaktiv visualisering av pensumalgoritmene i Algoritmer og datastrukturer (NTNU).
Velg kategori → algoritme, og stegg gjennom CLRS-pseudokoden mens dataene vises steg for steg.

innboforsikring-estimat.vercel.app

**Live** [algoritmevisualisering-alg-dat.vercel.app](https://algoritmevisualisering-alg-dat.vercel.app/)

**Innhold**

- Sortering (F1, F3–F5): INSERTION-SORT, MERGE-SORT, QUICKSORT, BISECT, HEAPSORT, COUNTING-SORT, RADIX-SORT, BUCKET-SORT, RANDOMIZED-SELECT, SELECT
- Datastrukturer (F2, F5, F9): CHAINED-HASH, TABLE-INSERT, MAX-HEAP-operasjoner (prioritetskø), binære søketrær, disjunkte mengder
- DP og grådighet (F6–F7): CUT-ROD, LCS-LENGTH, KNAPSACK, GREEDY-ACTIVITY-SELECTOR, HUFFMAN, GALE-SHAPLEY
- Graf (F8–F12): BFS, DFS, TOPOLOGICAL-SORT, SCC (Kosaraju), MST-KRUSKAL, MST-PRIM, BELLMAN-FORD, DAG-SHORTEST-PATHS, DIJKSTRA, FLOYD-WARSHALL, TRANSITIVE-CLOSURE, JOHNSON, FORD-FULKERSON

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
