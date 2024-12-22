<h1 align="center">
 <img height="100px" src="https://raw.githubusercontent.com/FortNbreak/Plauri/main/plauri.png" />
 <br />
 Plauri
</h1>

Plauri is an app that is the Plex web interface but in rust and tauri targeted at lower-end PCs.

## Key features
- **Space Efficent** - Plauri is very space efficent coming in at a whopping 8.77 MB (97.79% smaller than the Plex Desktop app)
- **Lightweight** - Plauri uses tauri so it does not use much RAM nor CPU.

## Tests
So I ran some tests. Here are the results

*RAM Usage Tests*
- IDLE - Sitting on idle (Home Page), the Plex desktop app was at 1.3 GB while Plauri was using ~400 MB RAM.
- Watching - While watching a movie in 4K, the Plex desktop app was at 1.4 GB while Plauri was using ~500 MB RAM.

*CPU Usage Tests*
Im not going to lie here. CPU-wise, Plex Desktop wins. 😔
- IDLE - Sitting on idle (Home Page), the Plex desktop app was using 0% CPU while Plauri was using ~3%.
- Watching - While watching a movie in 4K, the Plex desktop app was using 0.3% CPU while Plauri was using ~6%

*GPU Usage Tests*
- IDLE - Sitting on idle (Home Page), the Plex desktop app was using 0% GPU while Plauri was using ~0%
- Watching - While watching a movie in 4K, the Plex desktop app was using ~70% GPU while Plauri was using ~20%

