# mesa-27.0.1-glib-2.31-ubuntu20.04-linux-wayland-graphics
vulkan.h , new generation rebuild , wayland mesa

link all python , mesa-27.0.0 , ubuntu ,20.04

Ubuntu 20.04

Download mesa install sh script 

$ chmod -R a+rwx ./mesa-original_build-backup.sh && sudo ./mesa-original_build-backup.sh

My flags meson | потом помотрю можно ли что то еще включить или не стоит по скольку реакция может быть разной и где сделаешь то потом и в безопасный режим не зайдёт , а где то и добавит производительности как в этом случае мне удалось когда то получить avx.so и avx2.so и еще некоторые библиотеки включая pipe библиотеки.

-Dandroid-stub=false -Dbuild-aco-tests=false -Dbuild-tests=false -Dd3d-drivers-path= -Ddri-drivers-path= '-Ddri-drivers=['"'"'auto'"'"']' -Ddri-search-path= -Ddri3=auto -Degl-lib-suffix= -Degl=auto '-Dgallium-drivers=['"'"'auto'"'"']' -Dgallium-extra-hud=false -Dgallium-nine=false -Dgallium-omx=auto -Dgallium-opencl=disabled -Dgallium-va=auto -Dgallium-vdpau=auto -Dgallium-xa=auto -Dgallium-xvmc=auto -Dgbm=auto -Dgles-lib-suffix= -Dgles1=auto -Dgles2=auto -Dglvnd=false -Dglx-direct=true -Dglx-read-only-text=false -Dglx=auto -Dinstall-intel-gpu-tests=false -Dlibunwind=auto -Dllvm=auto -Dlmsensors=auto -Domx-libs-path= -Dopencl-spirv=false -Dopengl=true -Dosmesa-bits=8 -Dosmesa=none -Dplatform-sdk-version=25 '-Dplatforms=['"'"'auto'"'"']' -Dpower8=auto -Dprefer-iris=true -Dselinux=false -Dshader-cache=auto -Dshared-glapi=auto -Dshared-llvm=auto -Dshared-swr=true '-Dswr-arches=['"'"'avx'"'"',$ '"'"'avx2'"'"']' '-Dtools=[]' -Dva-libs-path= -Dvalgrind=auto -Dvdpau-libs-path= -Dvulkan-device-select-layer=false '-Dvulkan-drivers=['"'"'auto'"'"']' -Dvulkan-icd-dir= -Dvulkan-overlay-layer=false -Dxlib-lease=auto -Dxvmc-libs-path= -Dzstd=aut
