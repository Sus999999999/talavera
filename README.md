# Talavera Dolores (tienda_talavera)

Proyecto del manual "Talavera Dolores: tienda móvil completa" (TDD, Flutter).

## Cómo usarlo
```
flutter create tienda_talavera
cd tienda_talavera
# copia encima: lib/  test/  pubspec.yaml  (reemplaza los generados)
rm test/widget_test.dart        # el de plantilla referencia MyApp y rompe flutter test
flutter pub get
flutter test
flutter run
```
Pasarela y servidor de cuentas SIMULADOS: nunca procesan dinero real.
Tarjetas de prueba: 4242 4242 4242 4242 (aprueba), 4000 0000 0000 0002 (rechaza),
4000 0000 0000 9995 (fondos insuficientes). Cupones: DOLORES10, TALAVERA15.
