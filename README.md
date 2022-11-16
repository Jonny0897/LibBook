# LibBook

## Micro-Frontend by Nx - https://nx.dev/getting-started/intro
## To create workspace :
       npx create-nx-workspace@latest
## Run:
       cd apps:                   > nx serve lib-book
       serve the application:     > npx nx serve api
       build the application:     > npx nx build api
       test the application:      > npx nx test api

## Directory "apps"
       "lib-book": is th angular application.
       "lib-book-e2e": for test


## Share Codes - LIBRARY
       In libs there are all codes or components/ui which is shared in the other part of codes
       Make sure the library is imported in app.module.ts of "lib-book" project

              generate library:                     > nx g @nrwl/workspace:lib name-library
              generate library angular component:   > npx nx g @nrwl/angular:lib ui
              to add component:                     > npx nx g component nameOfComponent --project=ui --export           to use the ui-component take the selector -> ex. <ui-component>


