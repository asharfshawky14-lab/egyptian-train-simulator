# Egyptian Train Simulator — محاكي القطار المصري

3D Egyptian Train Simulator - Drive an ENR diesel locomotive from Cairo to Alexandria from the driver's cabin, with realistic Egyptian train, stations, signals, and passengers.

## Play

Open `index.html` in a browser (no build step, no server needed). Works on desktop and on phone.

## Route — الخط

Cairo (Ramses) → Benha → Tanta → Damanhur → Alexandria

القاهرة (محطة مصر) ← بنها ← طنطا ← دمنهور ← الإسكندرية

## The train — القطار

- Realistic detailed ENR diesel locomotive (dark blue with white / light-blue stripe, "سكك حديد مصر ENR") and five air-conditioned second-class coaches (silver/white with blue stripe).
- Detailed driver's cabin: dashboard with live gauges (speed, brake pressure, main reservoir, RPM), signal/door/engine lamps, working throttle and brake levers, horn / lights / doors / emergency buttons, wipers, mirrors, seats, ceiling fan, fire extinguisher, and timetable clipboard.
- Realistic Egyptian passengers on the platforms: men in galabeya with taqiyah/turban, women in hijab and abaya, children, an elder with a cane, and a station worker in blue uniform waving a green flag. Some passengers walk along the platform.

## Controls — التحكم

### Keyboard (computer)

- `W` / `↑` — throttle up (increase speed)
- `S` / `↓` — throttle down / brake
- `A` / `D` — brake
- `H` — horn
- `E` — open / close doors
- `C` — switch camera (cabin / outside)
- Fullscreen button — full-screen play

### Phone (touch)

- Draggable yellow throttle lever and red brake lever, `+` / `−` buttons, big red emergency-brake button, horn and doors buttons.
- Fullscreen button fills the phone screen.
- Camera button switches between the driver's cabin and an outside orbit camera — drag to look around the whole train, pinch to zoom.

## Gameplay — طريقة اللعب

- Control speed with the throttle and brakes, respect the speed limits (120 / 60 / 40 km/h near stations) and the green / yellow / red signals.
- Stop accurately at each station platform, open the doors, pick up passengers, and arrive on time to score points.
- Overspeed and signal violations lose points. Your grade is shown on the end screen, with a replay button.

## Sound — الصوت

Diesel engine sound that rises with speed and throttle, wheel clack on the rail joints, brake sounds, station whistle, and horn — all generated with Web Audio (starts on first tap / click).

## Files

- `index.html` — the whole game (Three.js, in one file)
- `assets/three.min.js` — Three.js library (bundled, works offline)
