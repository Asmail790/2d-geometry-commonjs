# Todo 
fix dynamic imports in dist folder to not import src folder
  - fix "get box(): import("2d-geometry/src").Box;" in "node_modules/2d-geometry/dist/classes/Quadratic.d.ts" to point do "dist" instead of "src" folder.
  - fix "get box(): import("2d-geometry/src/classes/Box").Box;" in node_modules/2d-geometry/dist/classes/Edge.d.ts to point do "dist" folder instead of "src" folder.
