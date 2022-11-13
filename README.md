En este video hemos implementado el loading spinner.
Hemos creado un componente nuevo LoadingSpinner y hemos inicializado la store con el reducer correspondiente a los datos del login, que es el spinner,
el estado es un objeto con una propiedad showLoading de tipo boolean. El reducer tendra una propiedad shared, y el valor es el sharedReducer
Despachamos la accion de pasar el boolean showLoading de false a true en el componente login, justo antes de pasar el email y password al service, 
y volvemos a despachar la accion de pasar el boolean showLoading de true a false de nuevo, en los effects del login, justo despues de haber enviado
el email y password al service