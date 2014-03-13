demo_mixta_android
==================

Este proyecto es una prueba de concepto de aplicaciones mixtas en Android.

Consta de un menú nativo con dos opciones:

1. Vista login
	En esta vista se ha incluido una webview que muestra una pantalla de login diseñada usando Twitter Boostrap para facilitar el diseño adaptativo.

2. Vista Mapa
	En esta vista se ha incluido un componente Google Maps nativo que muestra un mapa centrado programáticamente.

El desarrollo de las vistas se ha realizado mediante layouts y fragments:
	- activity_main que contiene el DrawerLayout (Menú lateral)
	- drawer_list_item que cotiene un item del menú
	- webview_fragment que contiene la webview que muestra el login
	- map_fragment que contiene el mapa nativo
