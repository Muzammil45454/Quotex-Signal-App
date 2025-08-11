# QuotexSignalApp

Short: Ye project live-market capable Android app hai jo Quotex websocket/token field support karta hai + fallback public feed (Binance) jab token na ho. Signal engine: EMA9/EMA21 + RSI14 + higher-timeframe trend + volume filter. Fast tick-refresh mode included.

## How to build (local)

1. Install Android Studio and JDK 11/17.
2. Open this folder as Android Studio project.
3. Put your Quotex demo session token in `app/src/main/assets/config.json` or enter it in app Settings UI after installing.
4. In terminal: `./gradlew assembleDebug` (Linux/mac) or `gradlew.bat assembleDebug` (Windows).
5. Debug APK will be in `app/build/outputs/apk/debug/app-debug.apk`.

Important
- Always test on a demo account.
- No accuracy guarantee. Backtest on demo before trading real money.
