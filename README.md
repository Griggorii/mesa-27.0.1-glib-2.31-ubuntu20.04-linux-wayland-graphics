# mesa-27.0.1-glib-2.31-ubuntu20.04-linux-wayland-graphics
vulkan.h , new generation rebuild , wayland mesa , mesa 256 levels grayscale

link all python , mesa-27.0.1 , ubuntu ,20.04

Ubuntu 20.04

Download mesa install sh script https://github.com/Griggorii/mesa-27.0.1-glib-2.31-ubuntu20.04-linux-wayland-graphics/releases/tag/ubuntu-20.04-glib-2.31 

$ chmod -R a+rwx ./mesa-27.0.1-install-ubuntu-20.04.sh && sudo ./mesa-27.0.1-install-ubuntu-20.04.sh

check info command:

$ glxinfo

Recomendation install mesa dev link cean optional

$ sudo rm -rf  /usr/lib/x86_64-linux-gnu/libXvMCr600.so.1 /usr/lib/x86_64-linux-gnu/libXvMCr600.so.1.0 /usr/lib/x86_64-linux-gnu/libXvMCr600.so.1.0.0 /usr/lib/x86_64-linux-gnu/libXvMCnouveau.so.1 /usr/lib/x86_64-linux-gnu/libXvMCnouveau.so.1.0 /usr/lib/x86_64-linux-gnu/libXvMCnouveau.so.1.0.0

Drirc https://github.com/Griggorii/drirc_acceleration_idea

Test drirc

$ LIBGL_DEBUG=verbose vblank_mode=0 glxgears

$ LIBGL_DEBUG=verbose vblank_mode=1 glxgears

Test multithread 2D https://www.shadertoy.com/view/3lsSzf replace string parameter HW_PERFORMANCE 0 to 1 

#if HW_PERFORMANCE==1

Compiled

My flags meson | потом помотрю можно ли что то еще включить или не стоит по скольку реакция может быть разной и где сделаешь то потом и в безопасный режим не зайдёт , а где то и добавит производительности как в этом случае мне удалось когда то получить avx.so и avx2.so и еще некоторые библиотеки включая pipe библиотеки.

-Dandroid-stub=false -Dbuild-aco-tests=false -Dbuild-tests=false -Dd3d-drivers-path= -Ddri-drivers-path= '-Ddri-drivers=['"'"'auto'"'"']' -Ddri-search-path= -Ddri3=auto -Degl-lib-suffix= -Degl=auto '-Dgallium-drivers=['"'"'auto'"'"']' -Dgallium-extra-hud=false -Dgallium-nine=false -Dgallium-omx=auto -Dgallium-opencl=disabled -Dgallium-va=auto -Dgallium-vdpau=auto -Dgallium-xa=auto -Dgallium-xvmc=auto -Dgbm=auto -Dgles-lib-suffix= -Dgles1=auto -Dgles2=auto -Dglvnd=false -Dglx-direct=true -Dglx-read-only-text=false -Dglx=auto -Dinstall-intel-gpu-tests=false -Dlibunwind=auto -Dllvm=auto -Dlmsensors=auto -Domx-libs-path= -Dopencl-spirv=false -Dopengl=true -Dosmesa-bits=8 -Dosmesa=none -Dplatform-sdk-version=25 '-Dplatforms=['"'"'auto'"'"']' -Dpower8=auto -Dprefer-iris=true -Dselinux=false -Dshader-cache=auto -Dshared-glapi=auto -Dshared-llvm=auto -Dshared-swr=true '-Dswr-arches=['"'"'avx'"'"',$ '"'"'avx2'"'"']' '-Dtools=[]' -Dva-libs-path= -Dvalgrind=auto -Dvdpau-libs-path= -Dvulkan-device-select-layer=false '-Dvulkan-drivers=['"'"'auto'"'"']' -Dvulkan-icd-dir= -Dvulkan-overlay-layer=false -Dxlib-lease=auto -Dxvmc-libs-path= -Dzstd=aut
