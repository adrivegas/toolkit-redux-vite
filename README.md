# toolkit-redux-vite
Aplicación basada en el patrón redux, en la cual se trabajan temas como: Redux,  Store , Middlewares,  Dispatch,  Actions,  State,  Acciones asíncronas,  RTK Query,  Redux Toolkit y  Slices

# Snippet y Gists de Slice
Agregamos el siguiente código dentro de vs code snippets/javascript.json, para crear un slice de Redux 
rápidamente con redux-slice + tab:

	<!-- "Crear un slice de Redux": {
		"prefix": "redux-slice",
		"body": [
			"import { createSlice } from '@reduxjs/toolkit';",
			"",
			"export const ${1:template}Slice = createSlice({",
			" name: '${1:template}',",
			" initialState: {",
			" counter: 10",
			" },",
			" reducers: {",
			" increment: (state, /* action */ ) => {",
			" state.counter += 1;",
			" },",
			" }",
			"});",
			"// Action creators are generated for each case reducer function",
			"export const { increment } = ${1:template}Slice.actions;"
		],
		"description": "Crear un slice de Redux"
	} -->

