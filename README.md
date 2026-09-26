
# AnestesiaCalc - designed by Alejo Montes
# App Android + iOS

## 📱 INSTALACIÓN RÁPIDA (PWA - funciona Android e iOS sin compilar)
Esta es la forma más rápida y funciona en ambos sistemas:

ANDROID:
1. Abre index.html en Chrome
2. Menú ⋮ → "Instalar app" / "Agregar a pantalla principal"
3. Queda como app nativa offline

iOS (iPhone/iPad):
1. Abre index.html en Safari
2. Botón compartir (cuadrado con flecha) → "Agregar a pantalla de inicio"
3. Queda como app nativa

## 🤖 GENERAR APK REAL ANDROID (.apk / .aab para Play Store)
Requisitos: Node.js instalado

```
npm install
npx cap add android
npx cap copy android
npx cap open android
```
En Android Studio: Build → Build Bundle/APK → APK
El APK sale en android/app/build/outputs/apk/debug/

Para .aab (Play Store): Build → Build Bundle → .aab

## 🍎 GENERAR IPA REAL iOS (.ipa para App Store)
Requisitos: Mac con Xcode

```
npx cap add ios
npx cap copy ios
npx cap open ios
```
En Xcode: Product → Archive → Distribute App

## Firma incluida
En esquina inferior derecha: "designed by Alejo Montes" color cian #00E5FF con fondo contraste

Versión: 1.0.0
Modelo: Eleveld Propofol + Minto Remifentanil + Scott Fentanil
Ajuste ke0 por edad real
