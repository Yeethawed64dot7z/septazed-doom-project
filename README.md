# septazed-doom-project
i will try to make this zdoom based because gzdoom is still in some development.
zdoom does have a better options menu than prboom+ imo so we're going with the latter
by team septazed (i will add members as i go if they contributed)
right now it's just only Yeethawed64.7z if you want to join i will put my discord server here later.
--------------------------------------------------
~ the planned features

~on the fly pwad patching by keeping IWAD contents loaded onto a cached temporarily written on the drive via .CACHE files 
~directX support (i think Gz does all i know is it has vulkan and opengl)
~local p2p server support (this is going to be agonizing)
~vr has already been done but the issue with vr is it is way too ridiculous to code
~load polys based on how far O.O.S. it is (customizable) 0-all polys
~somehow in some ridiculous way get raytracing to work.
~3d models (i'll emphasize more later)
~auto designate setting based on hardware and manage to get a fully functional pre launch options menu with lump autodetection.
~lump caching with which lumps it changes and check for acs, Zscript, and Decorate or any type of required script (i will elaborate on this more a bit later)
~texturable surfaces with light scattering (default being minimal to no reflection)
---------------------------------------------------
Problems in theory
i am relying on suport from you guys more or less (not financially) but about the raytracing considering i LITERALLY CANNOT DO IT MYSELF i do not have an rtx and do not plan to get one any time soon
local p2p will have to be duels or something and i do not know how to send inputs every tic which will be a problem
demo functions will be really difficult unless its input only with dooms pseudo rng and not real time rng
make the damned sourceport zdoom compatible and be able to at least have pwad, and pk3 file compatible.
lump caches will be as big as the wad itself so in order to optimize it only save the replaced IWAD lumps even then any other replaced pwad lumps like chex 1 being over ultimate doom so by doing that we would have to prioritize the Iwad 
