# Middle-earth interactive preview

Adapted from https://github.com/earthwalker17/map-of-middle-earth at commit 696e968e9d550327beda9e663ef5aec6961583c9.
Original code and authored models: MIT (LICENSE). Fonts: OFL files retained. Terrain detail textures: Poly Haven CC0; see CREDITS.md.

Geographic data: ME-DEM (monks, Redrobes, SeerBlue, jvangeld), ME-GIS (monks, SeerBlue, jvangeld; Andrew Heiss), Arda packaging (bburns, GeoPackage conversion by tetrakai1). The upstream credits state that DEM/vector licensing is uncertain and ME-GIS terms request permission; the code MIT license does not grant rights to those data. This preview includes locally baked derivatives, unlike the upstream source repository distribution. Full original attribution and statements are retained in CREDITS.md.

This non-commercial fan prototype uses a /middle-earth/ deployment base. Large masks are losslessly split and reconstructed with full SHA-256 verification. No terrain detail was reduced. No film, music, reference-image collection, source credentials, development caches or raw DEM inputs are included.

Controls: choose a shot in the upper-right menu; orbit/pan/zoom using standard OrbitControls. Requires a modern WebGPU-capable browser and HTTPS. Current quality is preview. Known limitation: rivendell-close has strong foreground waterfall occlusion.

Validation: TypeScript and production build passed. All 10 baked asset hashes pass after reassembly; all static files <=25 MiB. Earlier localhost rendering verified continent and Hobbiton; this GitHub build was statically validated for the /middle-earth/ prefix. No final deployed visual-quality claim is made here.
