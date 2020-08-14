# dxvk-async

Patched DXVK binaries.

DXVK: https://github.com/doitsujin/dxvk/releases

Async-pipeline-patch: https://github.com/Sporif/dxvk-async


The Async patch (with further adjustments) has already been worked into the custom Wine version of GloriousEggroll since Proton-5.8-GE-1-MF. 

https://github.com/GloriousEggroll/proton-ge-custom/releases

To use the async patch from within the custom Wine version with Lutris: 
go to System Options, simply set Environment Variables to DXVK_ASYNC 1

To visually reflect the change: DXVK_HUD fps,gpuload,pipelines

For more detailed information see the links above.
