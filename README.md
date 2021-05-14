Build library:

    cd ./lib
    ng build lib

Run dev server:

    cd ./app
    npm i
    npm start

Add `<lib-lib></lib-lib>` to `./app/src/app.component.html`, save:

    Error: Symbol LibComponent declared in /home/bart/IdeaProjects/angular12/lib/dist/lib/lib/lib.component.d.ts is not exported from lib (import into /home/bart/IdeaProjects/angular12/app/src/app/app.component.ts)
    at AbsoluteModuleStrategy.emit (/home/bart/IdeaProjects/angular12/app/node_modules/@angular/compiler-cli/src/ngtsc/imports/src/emitter.js:171:23)
    at ReferenceEmitter.emit (/home/bart/IdeaProjects/angular12/app/node_modules/@angular/compiler-cli/src/ngtsc/imports/src/emitter.js:72:44)
    at /home/bart/IdeaProjects/angular12/app/node_modules/@angular/compiler-cli/src/ngtsc/annotations/src/component.js:529:49
    at Array.map (<anonymous>)
    at ComponentDecoratorHandler.resolve (/home/bart/IdeaProjects/angular12/app/node_modules/@angular/compiler-cli/src/ngtsc/annotations/src/component.js:528:64)
    at TraitCompiler.resolve (/home/bart/IdeaProjects/angular12/app/node_modules/@angular/compiler-cli/src/ngtsc/transform/src/compilation.js:413:50)
    at /home/bart/IdeaProjects/angular12/app/node_modules/@angular/compiler-cli/src/ngtsc/core/src/compiler.js:607:31
    at ActivePerfRecorder.inPhase (/home/bart/IdeaProjects/angular12/app/node_modules/@angular/compiler-cli/src/ngtsc/perf/src/recorder.js:64:24)
    at NgCompiler.resolveCompilation (/home/bart/IdeaProjects/angular12/app/node_modules/@angular/compiler-cli/src/ngtsc/core/src/compiler.js:606:31)
    at NgCompiler.<anonymous> (/home/bart/IdeaProjects/angular12/app/node_modules/@angular/compiler-cli/src/ngtsc/core/src/compiler.js:481:54)
