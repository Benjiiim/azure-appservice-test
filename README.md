# Azure AppService Test

This repo is intended to test azure app service with lwip

## Error

    Counting objects: 5, done.
    Delta compression using up to 4 threads.
    Compressing objects: 100% (3/3), done.
    Writing objects: 100% (3/3), 360 bytes | 0 bytes/s, done.
    Total 3 (delta 1), reused 0 (delta 0)
    remote: Updating branch 'master'.
    remote: Updating submodules.
    remote: Preparing deployment for commit id '30672105be'.
    remote: Generating deployment script.
    remote: Running deployment command...
    remote: Handling node.js deployment.
    remote: KuduSync.NET from: 'D:\home\site\repository' to: 'D:\home\site\wwwroot'
    remote: Copying file: 'package.json'
    remote: Looking for app.js/server.js under site root.
    remote: Using start-up script server.js
    remote: Generated web.config.
    remote: Node.js versions available on the platform are: 0.6.20, 0.8.2, 0.8.19, 0.8.26, 0.8.27, 0.8.28, 0.10.5, 0.10.18, 0.10.21, 0.10.24, 0.10.26, 0.10.28, 0.10.29, 0.10.31, 0.10.32, 0.10.40, 0.12.0, 0.12.2, 0.12.3, 0.12.6, 4.0.0, 4.1.0, 4.1.2, 4.2.1, 4.2.2, 4.2.3, 4.2.4, 4.3.0, 4.3.2, 4.4.0, 4.4.1, 4.4.6, 4.4.7, 4.5.0, 4.6.0, 4.6.1, 5.0.0, 5.1.1, 5.3.0, 5.4.0, 5.5.0, 5.6.0, 5.7.0, 5.7.1, 5.8.0, 5.9.1, 6.0.0, 6.1.0, 6.2.2, 6.3.0, 6.5.0, 6.6.0, 6.7.0, 6.9.0, 6.9.1, 7.0.0.
    remote: Selected node.js version 6.9.1. Use package.json file to choose a different version.
    remote: Selected npm version 3.10.8
    remote: Updating iisnode.yml at D:\home\site\wwwroot\iisnode.yml
    remote: .
    remote: npm WARN deprecated lodash-node@2.4.1: This package is discontinued. Use lodash@^4.0.0.
    remote: .................
    remote:
    remote: > lwip@0.0.9 install D:\home\site\wwwroot\node_modules\lwip
    remote: > node-gyp rebuild
    remote:
    remote:
    remote: D:\home\site\wwwroot\node_modules\lwip>if not defined npm_config_node_gyp (node "D:\Program Files (x86)\npm\3.10.8\node_modules\npm\bin\node-gyp-bin\\..\..\node_modules\node-gyp\bin\node-gyp.js" rebuild )  else (node "" rebuild )
    remote: Building the projects in this solution one at a time. To enable parallel build, please add the "/m" switch.
    remote:   init.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_decoder.vcxproj]
    remote:   util.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_decoder.vcxproj]
    remote:   buffer_worker.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_decoder.vcxproj]
    remote:   jpeg_decoder.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_decoder.vcxproj]
    remote:   png_decoder.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_decoder.vcxproj]
    remote:   gif_decoder.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_decoder.vcxproj]
    remote:   win_delay_load_hook.cc
    remote:   init.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_encoder.vcxproj]
    remote:   jpeg_worker.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_encoder.vcxproj]
    remote:   png_worker.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_encoder.vcxproj]
    remote:   gif_worker.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_encoder.vcxproj]
    remote:   win_delay_load_hook.cc
    remote:   init.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_image.vcxproj]
    remote:   image.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_image.vcxproj]
    remote:   resize_worker.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_image.vcxproj]
    remote:   rotate_worker.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_image.vcxproj]
    remote:   blur_worker.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_image.vcxproj]
    remote:   crop_worker.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_image.vcxproj]
    remote:   mirror_worker.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_image.vcxproj]
    remote:   pad_worker.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_image.vcxproj]
    remote:   sharpen_worker.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_image.vcxproj]
    remote:   hsla_worker.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_image.vcxproj]
    remote:   opacify_worker.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_image.vcxproj]
    remote:   paste_worker.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_image.vcxproj]
    remote:   setpixel_worker.cpp
    remote: D:\home\site\wwwroot\node_modules\lwip\src\lib\cimg\CImg.h(75): fatal error C1083: Cannot open include file: 'cstdarg': No such file or directory [D:\home\site\wwwroot\node_modules\lwip\build\lwip_image.vcxproj]
    remote:   win_delay_load_hook.cc
    remote: gyp ERR! build error
    remote: gyp ERR! stack Error: `msbuild` failed with exit code: 1
    remote: gyp ERR! stack     at ChildProcess.onExit (D:\Program Files (x86)\npm\3.10.8\node_modules\npm\node_modules\node-gyp\lib\build.js:276:23)
    remote: gyp ERR! stack     at emitTwo (events.js:106:13)
    remote: gyp ERR! stack     at ChildProcess.emit (events.js:191:7)
    remote: gyp ERR! stack     at Process.ChildProcess._handle.onexit (internal/child_process.js:215:12)
    remote: gyp ERR! System Windows_NT 6.2.9200
    remote: gyp ERR! command "D:\\Program Files (x86)\\nodejs\\6.9.1\\node.exe" "D:\\Program Files (x86)\\npm\\3.10.8\\node_modules\\npm\\node_modules\\node-gyp\\bin\\node-gyp.js" "rebuild"
    remote: gyp ERR! cwd D:\home\site\wwwroot\node_modules\lwip
    remote: gyp ERR! node -v v6.9.1
    remote: gyp ERR! node-gyp -v v3.4.0
    remote: gyp ERR! not ok
    remote: .........
    remote: npm ERR! Windows_NT 6.2.9200
    remote: npm ERR! argv "D:\\Program Files (x86)\\nodejs\\6.9.1\\node.exe" "D:\\Program Files (x86)\\npm\\3.10.8\\node_modules\\npm\\bin\\npm-cli.js" "install" "--production"
    remote: npm ERR! node v6.9.1
    remote: npm ERR! npm  v3.10.8
    remote: npm ERR! code ELIFECYCLE
    remote: Failed exitCode=1, command="D:\Program Files (x86)\nodejs\6.9.1\node.exe" "D:\Program Files (x86)\npm\3.10.8\node_modules\npm\bin\npm-cli.js" install --production
    remote:
    remote: An error has occurred during web site deployment.
    remote: npm ERR! lwip@0.0.9 install: `node-gyp rebuild`
    remote: npm ERR! Exit status 1
    remote: npm ERR!
    remote: npm ERR! Failed at the lwip@0.0.9 install script 'node-gyp rebuild'.
    remote: npm ERR! Make sure you have the latest version of node.js and npm installed.
    remote: npm ERR! If you do, this is most likely a problem with the lwip package,
    remote: npm ERR! not with npm itself.
    remote: npm ERR! Tell the author that this fails on your system:
    remote: npm ERR!     node-gyp rebuild
    remote: npm ERR! You can get information on how to open an issue for this project with:
    remote: npm ERR!     npm bugs lwip
    remote: npm ERR! Or if that isn't available, you can get their info via:
    remote: npm ERR!     npm owner ls lwip
    remote: npm ERR! There is likely additional logging output above.
    remote:
    remote: npm ERR! Please include the following file with any support request:
    remote: npm ERR!     D:\home\site\wwwroot\npm-debug.log
    remote:
    remote: Error - Changes committed to remote repository but deployment to website failed.
    To https://benjatms@testyes.scm.azurewebsites.net:443/testyes.git
    7878f39..3067210  master -> master