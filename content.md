<!-- Title slide. -->
<!-- .slide: data-background="media/img/aframe.jpg" -->

<div class="talk-title">
  <h1>A-Frame School</h1>
  <h3>Um curso interativo de WebVR</h3>
  <p class="talk-info">
    <b><a href="https://aframe.io">aframe.io</a></b>
  </p>
</div>

------

## Prólogo

<!-- .slide: data-background="media/img/aframe.jpg" -->

> Usando [Glitch](https://glitch.com), a School irá ensinar exercícios passo a passo
> para você aprender [WebVR](https://webvr.rocks)! A School tem
> sessões indo para &larr; e &rarr; mas também subseções aindo para **&uarr; e
> &darr;**:

<img class="stretch" data-src="media/img/navigation.jpg">

**Navegue &darr;**

---

### Recursos

1. [Documentação e FAQ](https://aframe.io/docs/)
2. [Obtenha ajuda no Slack](https://aframe.io/community/#slack)
3. [Faça perguntas no Stack Overflow](http://stackoverflow.com/questions/ask/?tags=aframe)
4. Se você estiver em uma oficina, por favor, levante a mão se você tiver uma pergunta!

**Navegue &rarr;**


<!-- Lessons start below. -->


------

## Glitch &mdash; Introdução

> A School usa [Glitch](https://glitch.com) como seu ambiente de aprendizado e desenvolvimento para A-Frame.

<img class="stretch" data-src="media/img/glitch.jpg">

- Glitch permite desenvolver no navegador
- Glitch permite **modificar** projetos já criados para criar novos
- Glitch publica e hospeda instantaneamente seu site com uma URL (exemplo:
  `https://aframe.glitch.me`)
- Glitch atualiza seu site ao vivo a cada alteração de código
- Glitch permite que várias pessoas desenvolvam no mesmo projeto

*Se você está interessado em criar um ambiente de desenvolvimento local, pule &darr;*

---

## Glitch &mdash; Modificando um projeto existente

> Glitch permite que você remixe/fork um projeto existente para usá-lo como base para o seu novo projeto. Antes de
> iniciar, recomendamos conectar o Glitch a uma conta no GitHub. Depois que você modificar, Glitch lhe dará um projeto aleatório e
> URL, que você pode mudar.

<img class="stretch" data-src="media/img/glitch2.jpg">

[Remix the A-Frame Starter Glitch](https://glitch.com/~aframe/)  <!-- .element: class="cta-button glitch" -->

---

## Glitch &mdash; Editando o seu código

> Depois de [remixar o A-Frame Starter Glitch](https://glitch.com/~aframe/), confira onde você estará editando seu código. Navegue no editor e veja que você pode até editar o código do servidor back-end, carregar recursos, criar novos arquivos ou convidar outras pessoas para editar com você!

<img class="stretch" data-src="media/img/glitch3.jpg">

---

## Glitch &mdash; Visualizando o seu projeto

> Depois que você editou, veja o projeto ao vivo.

<img class="stretch" data-src="media/img/glitch4.jpg">

---

## Glitch &mdash; Exportando o seu projeto

> Em qualquer momento, se você quer fazer download do seu projeto ou exportar para o GitHub, veja *Advanced Options* no menu. Ao fazer download o projeto vem em um arquivo `.tgz` que você pode descompactar. Para projetos A-Frame, você deve se preocupar com o que está na pasta `public/` e ignorar todo o código do lado do servidor.

<img class="stretch" data-src="media/img/glitch5.jpg">

Se você fizer download de um projeto, talvez esteja interessado em configurar um ambiente de desenvolvimento web na próxima seção **&darr;**. Ou próximo **&rarr;** para começar com A-Frame.

---

## [Optional] Set Up a Web Development Environment

> You can set up a full web development environment on your local machine, rather
> than use Glitch's online web development environment.

<img class="stretch" data-src="media/img/webdevenv1.jpg">

1. **Get a text editor:** [Atom](https://atom.io) is a good one to start with
2. **Set up a local server:** Download and run [Mongoose
Server](https://www.cesanta.com/products/binary) or run `python -m
SimpleHTTPServer` in a terminal
3. **Create a file `index.html`** and copy A-Frame code from the Glitch samples
4. **Run a local server** in the same directory as the HTML file
5. **Open the local server's URL** in your browser (e.g., `http://localhost:8000`)
6. **Make changes** to your HTML file and refresh your browser to see the changes
7. Optional: check out [ngrok](https://ngrok.io) to let any device on any
network have access to your local server

---

## [Optional] Set Up a Web Development Environment &mdash; Get a Text Editor

> [Atom](https://atom.io) is a good text editor to start if you don't have one.
> Other popular options are [Notepad++](https://notepad-plus-plus.org/),
> [Sublime](https://www.sublimetext.com/), [Brackets](http://brackets.io/), or
> [vim](http://www.vim.org/download.php).

<img class="stretch" data-src="media/img/webdevenv2.jpg">

---

## [Optional] Set Up a Web Development Environment &mdash; Set Up a Local Server

> You'll need a local HTTP server to serve your files to the browser.

<div class="captioned-image-row small">
  <div>
    <img data-src="https://cloud.githubusercontent.com/assets/8731271/24021623/10654d22-0a5f-11e7-9769-63cdff91637c.png">
    <a href="https://www.cesanta.com/products/binary">Mongoose Binary</a>
  </div>
  <div>
    <img data-src="https://www.python.org/static/opengraph-icon-200x200.png">
    <code>python -m SimpleHTTPServer 8080</code>
  </div>
  <div>
    <img data-src="https://www.echosteg.com/images/blog/standard/nodejs_logo.png">
    <a href="https://docs.npmjs.com/getting-started/installing-node">Node + npm + live-server</a>
  </div>
</div>

---

## [Optional] Set Up a Web Development Environment &mdash; Use ngrok

> Optionally, you can use [ngrok](https://ngrok.com/) to help develop your
> A-Frame project on a smartphone without having to do the local IP address
> dance.

1. Download and unzip [ngrok](https://ngrok.com/download/) anywhere
2. Run ngrok, providing it the port number of your local server (`./ngrok http 8080`)
3. In the output, ngrok will give you a URL with a bunch of letters and numbers (e.g., `https://abcdef123456.ngrok.io`)
4. Open that URL on another device on any network (such as a smartphone or another computer)

<img class="stretch" data-src="media/img/webdevenv3.jpg">

------

## Experimente exemplos do A-Frame

>Experimente exemplos em seu desktop ou smartphone do [A-Frame Homepage](https://aframe.io), [A-Frame Blog](https://aframe.io/blog/), ou [awesome-aframe](https://github.com/aframevr/awesome-aframe). Veja [webvr.rocks](https://webvr.rocks) para aprender a configurar WebVR para usar com headset.

<img data-src="media/img/examples.gif">

------

## Comece com *Hello, WebVR*

> A-Frame fornece elementos HTML fáceis de usar para iniciantes chamados de [primitives](https://aframe.io/docs/0.5.0/primitives/). Nas seções abaixo, modificaremos o básico por meio de atributos HTML (por exemplo, alterar cores, posições, rotações, escala) para ter uma ideia do funcionamento.

<img data-src="media/img/hellowebvr2.jpg">

<img class="stretch" data-src="media/img/hellowebvr.jpg">

---

## Comece com *Hello, WebVR* &mdash; Posição

> A posição define onde o objeto estará no espaço 3D (X, Y, Z) em metros. Mude a `position` do objeto dando valores aos atributos. [Leia sobre posições](https://aframe.io/docs/master/components/position.html).

[Remixe a lição no Glitch](https://glitch.com/~aframe-school-position)  <!-- .element: class="cta-button glitch" -->

1. Mova o cilindro para a esquerda *diminuindo* o valor X da `position`
2. Mova a caixa para cima *aumentando* o valor Y da `position`
3. Mova a esfera para trás, *diminuindo* o valor Z da `position`
4. **Extra:** Adicione `<a-ring>` como um filho de `<a-sphere>` e dê uma posição para ver posições relativas

<img class="stretch" data-src="media/img/positionresult.jpg">

[Veja o resultado](https://aframe-school-position.glitch.me/solution.html)  <!-- .element: class="cta-button" -->

---

## Comece com *Hello, WebVR* &mdash; Rotação
> A Rotação define a orientação dos objetos no espaço 3D (sobre os eixos X, Y, Z) em graus. Use a regra da mão direita para visualizar espacialmente a rotação. [Leia sobre rotações](https://aframe.io/docs/master/components/rotation.html).


[Remixe a lição no Glitch](https://glitch.com/~aframe-school-rotation)  <!-- .element: class="cta-button glitch" -->

1. Gire o cilindro em torno do eixo X para ver o fundo
2. Gire a caixa em torno do eixo Y para que a caixa fique com uma ponta achatada
3. **Extra:** Envolva o conteúdo da cena em uma `<a-entity>` (é tipo uma `<div>`) e dê a rotação para ver rotações relativas

<img class="stretch" data-src="media/img/rotationresult.jpg">

[Veja o resultado](https://aframe-school-rotation.glitch.me/solution.html)  <!-- .element: class="cta-button" -->

---

## Comece com *Hello, WebVR* &mdash; Adicione primitivos

> Adicione primitivos a cena adicionando elementos HTML sob `<a-scene>`. [Leia sobre rotações](https://aframe.io/docs/0.5.0/primitives/).

[Remixe a lição no Glitch](https://glitch.com/~aframe-school-primitives)  <!-- .element: class="cta-button glitch" -->

1. Adicione [`<a-torus-knot>`](https://aframe.io/docs/0.5.0/primitives/a-torus-knot.html) para a esquerda
2. Adicione [`<a-dodecahedron>`](https://aframe.io/docs/0.5.0/primitives/a-dodecahedron.html) para a direita
3. Adicione [`<a-text>`](https://aframe.io/docs/0.5.0/primitives/a-text.html) alinhado no centro

<img class="stretch" data-src="https://cloud.githubusercontent.com/assets/674727/24266010/9c57cbe4-0fc2-11e7-968f-168f3649d109.png">

[Veja o resultado](https://aframe-school-primitives.glitch.me/solution.html)  <!-- .element: class="cta-button" -->

------

## Adicione texturas &mdash; Carregando recursos

> Iremos adicionar texturas de imagem as malhas para aparecer mais que apenas uma cor sólida. [Encontre suas próprias imagens online](https://aframe.io/docs/0.5.0/introduction/faq.html#where-can-i-find-assets) e faça upload delas por meio da sessão de "assets" do Glich ou por meio do uploader no [cdn.aframe.io](https://cdn.aframe.io). Em qualquer caso, certifique-se de que está sendo servido com [CORS](https://developer.mozilla.org/docs/Web/HTTP/Access_control_CORS) e sob HTTPS.

<img class="stretch" data-src="media/img/glitchasset.jpg">

No Glitch abaixo **&darr;**, alguns recursos já serão fornecidos na seção de recursos (foto acima).

---

## Adicione texturas &mdash; Texturas de imagem

> Adicione no `src` atributos HTML com a URL da imagem. [Leia sobre como aplicar uma textura de imagem](https://aframe.io/docs/0.5.0/guides/#applying-an-image-texture).

[Remixe a lição no Glitch](https://glitch.com/~aframe-school-textures/)  <!-- .element: class="cta-button glitch" -->

1. Adicione uma textura de imagem ao "solo", `<a-plane>`
2. Adicione uma textura de imagem nas `<a-box>`
3. Adicione uma textura de imagem na `<a-sphere>`
4. Adicione uma textura de imagem no `<a-cone>`
5. Adicione uma textura de imagem ao plano de fundo, `<a-sky>`. Encontre [imagens 360&deg; do FLickr](https://www.flickr.com/groups/equirectangular/)

<img class="stretch" data-src="media/img/texture.jpg">

[Veja o resultado](https://aframe-school-textures.glitch.me/solution.html)  <!-- .element: class="cta-button" -->

------

## Abra o A-Frame Inspector

> Hit **`<ctrl> + <alt> + i`** on **any** A-Frame scene to pop open a visual
> editor, just like your browser's Dev Tools!  Try the Inspector on some of the
> [homepage examples](https://aframe.io/examples/). [Read about the
> Inspector](https://aframe.io/docs/master/guides/using-the-aframe-inspector.html).

<img class="stretch" data-src="media/img/inspector.gif">

---

## Open the A-Frame Inspector &mdash; Change Component Values

> Modify an entity by modifying its components on the right-hand panel. The
> Inspector knows about all A-Frame components, including community components.
>  This example includes an external [text-geometry
> component](https://www.npmjs.com/package/aframe-text-geometry-component), which
> the Inspector can modify the values of live.

[Open Example on Glitch](https://aframe-vaporwave.glitch.me)  <!-- .element: class="cta-button glitch" -->

1. Select one of the entities with text in the example
2. Change the [`text-geometry` component's](https://www.npmjs.com/package/aframe-text-geometry-component) `value` property

<img class="stretch" data-src="media/img/inspectorchange.jpg">

---

## Open the A-Frame Inspector &mdash; Attach Components from the Registry

> Use [physics components](https://github.com/donmccurdy/aframe-physics-system)
> from the [Registry](https://aframe.io/registry/) to add gravity and collisions.
> The Registry is a curated collection of A-Frame components. And the Inspector
> is hooked up to the Registry so we can add components from the Registry in the
> entity panel.

[Open Example on Glitch](https://aframe-vaporwave.glitch.me)  <!-- .element: class="cta-button glitch" -->

1. Add the `static-body` component to ground grid
2. Add the `dynamic-body` component to the torus knot (the purple pretzel in the back)
3. Increase the Y-position of the torus knot to make it higher up
4. Exit the Inspector

<img class="stretch" data-src="media/img/inspectorregistry.gif">

------

## Compose with Entity-Component &mdash; Break Primitives Down

> Behind the easy-to-use primitive elements, A-Frame is based on an
> entity-component architecture. Decompose the primitive elements in the
> *Hello, WebVR* example to `<a-entity>`s with their fundamental components.

[Remix Lesson on Glitch](https://glitch.com/~aframe-school-ecs)  <!-- .element: class="cta-button glitch" -->

[geometry]: https://aframe.io/docs/0.5.0/components/geometry.html
[material]: https://aframe.io/docs/0.5.0/components/material.html

1. Convert `<a-box>` to `<a-entity>` with [geometry component][geometry] and [material component][material]. Configure the geometry component to be `primitive: box`
2. Convert `<a-sphere>` to `<a-entity>` with geometry component and material component. Configure the geometry component to be `primitive: sphere`
3. Convert `<a-cylinder>` to `<a-entity>` with geometry component and material component. Configure the geometry component to be `primitive: cylinder`
4. Convert `<a-plane>` to `<a-entity>` with geometry component and material component. Configure the geometry component to be `primitive: plane`
5. Convert `<a-sky>` to `<a-entity>` with geometry component and material component. Configure the geometry component to be `primitive: sphere` with a large `radius: 3000`, and configure the material component to be `shader: flat` so we don't do expensive lighting calculations when we just need a flat color

[View Result](https://aframe-school-ecs.glitch.me/solution.html)  <!-- .element: class="cta-button" -->

---

## Compose with Entity-Component &mdash; Add a Light Source Sphere

> Use the entity-component pattern to add a sphere that also acts as a point
> light source. Mix together the geometry, material, and light components to
> compose this type of object.

1. Look for `<a-entity id="lightSphere">`
2. Attach the [geometry component](https://aframe.io/docs/0.5.0/components/geometry.html) configured to use `primitive: sphere` to the entity
3. Attach the [material component](https://aframe.io/docs/0.5.0/components/material.html) configured to use `color: #FFF` and `shader: flat` to the entity
4. Attach the [light component](https://aframe.io/docs/0.5.0/components/light.html) configured to use `type: point` to the entity
5. **Extra Credit:** Add the animation component from [the Registry](https://aframe.io/registry/) via a `<script>` tag. Attach the animation configured to use `property: position` and `dir: alternate` and `loop: true` and provide a position value for `to: <POSITION>`

[Remix Lesson on Glitch](https://glitch.com/~aframe-school-ecs-light-sphere)  <!-- .element: class="cta-button glitch" -->

<img class="stretch" data-src="https://cloud.githubusercontent.com/assets/674727/24060160/2c53a604-0b0f-11e7-9386-f83a3a9b4cfc.gif">>

[View Result](https://aframe-school-ecs-light-sphere.glitch.me/solution.html)  <!-- .element class="cta-button" -->

------

## Extend with Entity-Component &mdash; From the Registry

> [The Registry](https://aframe.io/registry/) is a great place to grab cool
> components that the community has added to A-Frame. Sort of like third-party
> plugins. Find community components from the Registry, copy their JS links,
> include them via a `<script>` tag, and use them straight from HTML.

1. Include [Particle
System](https://www.npmjs.com/package/aframe-particle-system-component). Attach
`<a-entity>`s with `particle-system` components configured to `preset: default`
and `preset: snow`. Open the Inspector to play with the values!
2. Include [Animation](https://www.npmjs.com/package/aframe-animation-component). Attach
animation to the sphere to throb its scale by configuring `animation` component
with `property: scale`, `loop: true`, and `to: 1.1 1.1 1.1`
3. Include [Outline Effect](https://www.npmjs.com/package/aframe-outline-effect). Drop in the
`<script>` and attach the `outline` component to the scene

[Remix Lesson on Glitch](https://glitch.com/~aframe-school-registry)  <!-- .element: class="cta-button glitch" -->

<img class="stretch" data-src="media/img/registryexample.gif">

[View Result](https://aframe-school-registry.glitch.me/solution.html)  <!-- .element class="cta-button" -->

------

## Use JavaScript

> Use JavaScript and DOM APIs to programmatically modify the scene and its
> entities. A-Frame is not just HTML; A-Frame provides access to JavaScript,
> DOM APIs, and three.js underneath for full control.  [Read about *Using
> JavaScript and DOM APIs* with
> A-Frame](https://aframe.io/docs/0.5.0/guides/using-javascript-and-dom-apis.html).

[Remix Lesson on Glitch](https://glitch.com/~aframe-school-js)  <!-- .element: class="cta-button glitch" -->

<img class="stretch" data-src="media/img/js.jpg">

To see JavaScript logs, we can open the browser's development console by
right-clicking the page, clicking *Inspect* or *Inspect Element*, and then
clicking the *Console* tab. When viewing solutions, we can see the results
through the browser console.

---

## Use JavaScript &mdash; Getting Entities

> Use
> [`document.querySelector()`](https://developer.mozilla.org/docs/Web/API/Document/querySelector)
> and
> [`document.querySelectorAll()`](https://developer.mozilla.org/docs/Web/API/Document/querySelectorAll)
> to get a reference to the scene and its entities.  [Read about querying for
> entities](https://aframe.io/docs/0.5.0/guides/using-javascript-and-dom-apis.html#getting-entities-by-querying-and-traversing).

[Remix Lesson on Glitch](https://glitch.com/~aframe-school-js)  <!-- .element: class="cta-button glitch" -->

1. Get a reference to the `<a-scene>` element using `var sceneEl = document.querySelector('a-scene');`
2. Get a reference to all `<a-entity>` elements using `sceneEl.querySelectorAll('a-entity');`
3. Get a reference to the box entity using `sceneEl.querySelector('#box');`
4. Get a reference to the sphere and cylinder entities in one `.querySelectorAll()` call by using multi-element selector
. Get a reference to the sphere and cylinder entities in one `.querySelectorAll()` call by adding and selecting HTML classes

[View Result](https://aframe-school-js.glitch.me/solution.html)  <!-- .element: class="cta-button" -->

---

## Use JavaScript &mdash; Modifying Entities

> Use
> [`Entity.setAttribute()`](https://aframe.io/docs/0.5.0/core/entity.html#setattribute-attr-value-componentattrvalue)
> to modify entities after retrieving them from the previous exercise. [Read
> about modifying
> entities](https://aframe.io/docs/0.5.0/guides/using-javascript-and-dom-apis.html#modifying-an-entity).

[Remix Lesson on Glitch](https://glitch.com/~aframe-school-js)  <!-- .element: class="cta-button glitch" -->

1. Change the box entity's `rotation` component
2. Change the cylinder entity's `geometry` component's `height` property
3. Change the sphere entity's `material` component's `metalness` property

[View Result](https://aframe-school-js.glitch.me/solution2.html)  <!-- .element: class="cta-button" -->

---

## Use JavaScript &mdash; Creating Entities

> Use [`document.createElement()`](https://developer.mozilla.org/docs/Web/API/Document/createElement)
> to create entities, `.setAttribute()` to configure them, and `.appendChild()`
> to add them to the scene.  [Read about creating
> entities](https://aframe.io/docs/0.5.0/guides/using-javascript-and-dom-apis.html#creating-an-entity-with-createelement).

[Remix Lesson on Glitch](https://glitch.com/~aframe-school-js)  <!-- .element: class="cta-button glitch" -->

1. In a JavaScript `for` loop, create and add 50 `<a-box>` elements with
random positions and scales (use `Math.random()`)

[View Result](https://aframe-school-js.glitch.me/solution3.html)  <!-- .element: class="cta-button" -->

---

## Use JavaScript &mdash; Handling Events

> Use
> [`.addEventListener()`](https://developer.mozilla.org/docs/Web/API/EventTarget/addEventListener)
> to register a handler function that will be called when an event is emitted.
> Then manually emit that event to see that handler function execute. Later we
> can use event listeners to change the scene based on user input or other
> events. [Read about events and event listeners with
> A-Frame](https://aframe.io/docs/0.5.0/guides/using-javascript-and-dom-apis.html#events-and-event-listeners).

[Remix Lesson on Glitch](https://glitch.com/~aframe-school-js)  <!-- .element: class="cta-button glitch" -->

1. Register an event listener on the box to listen to the `foo` event. In the
   handler function, change the box's color
2. Emit the `foo` event with
[`Entity.emit()`](https://aframe.io/docs/0.5.0/core/entity.html#emit-name-detail-bubbles)
and see the box change its color

[View Result](https://aframe-school-js.glitch.me/solution4.html)  <!-- .element: class="cta-button" -->

------

## Add Gaze-Based Cursor Interactions &mdash; Add Cursor Entity

> Use the gaze-based [`cursor`
> component](https://aframe.io/docs/0.5.0/components/cursor.html) to provide
> the ability to interact with entities (primarily for smartphones).  [Read
> about building a 360&deg; image
> gallery](https://aframe.io/docs/0.5.0/guides/building-with-components.html).

[Remix Lesson on Glitch](https://glitch.com/~aframe-school-cursor)  <!-- .element: class="cta-button glitch" -->

This lesson has all the event listeners hooked up already. We just need to add
an entity with the `cursor` component which will provide those events based on
user input.  Note these events are not provided by the browser, but through
A-Frame.

1. Add [`<a-camera>`](https://aframe.io/docs/0.5.0/components/camera.html) entity.
   Previously A-Frame was providing a default camera
2. Add [`<a-cursor>`](https://aframe.io/docs/0.5.0/components/cursor.html) entity
   as a child underneath the camera entity
3. Drag the camera around the click on the panels on desktop. On smartphones,
   stare at the panels to trigger clicks (i.e., gaze-based)

<img class="stretch" data-src="media/img/gaze.gif">

[View Result](https://glitch.com/~aframe-school-cursor)  <!-- .element: class="cta-button glitch" -->

---

## Add Gaze-Based Cursor Interactions &mdash; Handle Events

> Use the `click`, `mouseenter`, `mouseleave` events provided by the gaze-based
> [`cursor` component](https://aframe.io/docs/0.5.0/components/cursor.html) to
> change the properties of an object.

The Glitch code will have the project structure set up. We can add JavaScript
code inside the `handle-events` component, marked by the code comments.

[Remix Lesson on Glitch](https://glitch.com/~aframe-school-cursor-handler)  <!-- .element: class="cta-button glitch" -->

1. Attach our `controller-event-handler` to the cubes. We can attach to all of them at once through the mixin
2. Add an event listener to change the box's color on `mouseenter` event
3. Add an event listener to restore the box's color on `mouseleave` event

<img class="stretch" data-src="media/img/gazehandler.gif">

[View Result](https://aframe-school-cursor-handler.glitch.me/solution.html)  <!-- .element: class="cta-button glitch" -->

------

## Add 3D Models &mdash; glTF Model

> 3D models are like the images of 3D and VR applications, although a bit
> heavier. A 3D model is created beforehand in a 3D modeling program such as
> [Blender](https://www.blender.org/) and consists of vertices, textures,
> materials. We recommend using [glTF](https://github.com/KhronosGroup/glTF), a
> relatively new 3D file format standard tailored for the Web. glTF is like the
> JPG of 3D models.

[Remix Lesson on Glitch](https://glitch.com/~aframe-school-gltf-model)  <!-- .element: class="cta-button glitch" -->

1. Add the `https://cdn.aframe.io/test-models/models/virtualcity/VC.gltf` to
the `<a-asset-item id="model">`'s `src` attribute to preload the model
2. Add `#model` to the `<a-gltf-model>`'s `src` attribute to set and add the model

<img class="stretch" data-src="https://cloud.githubusercontent.com/assets/674727/24275925/63067074-0ff0-11e7-9440-7c855b9ea0fd.png">

[View Result](https://aframe-school-gltf-model.glitch.me/solution.html)  <!-- .element: class="cta-button" -->

---

## Add 3D Models &mdash; glTF Model Animations

> Models can come with animations. The model provided above has many animations
> of ships zooming across the city. In the previous Glitch, we've provided a simple
> `play-all-model-animations` component that we can attach to our model to play
> its animations. Continue working from your current Glitch.

1. Include the `animation-mixer` component via a `<script>` in the
`<head>` after the A-Frame script. This component is currently in the Registry,
and may one day be included with A-Frame. `https://unpkg.com/aframe-extras.animation-mixer@3.4.0/dist/aframe-extras.animation-mixer.js`
2. Attach the `animation-mixer` component to the `<a-gltf-model>` by
setting it via an HTML attribute `animation-mixer`. By default, this will play all
the animations of the model at once.

<img class="stretch" data-src="media/img/gltf.gif">

[View Result](https://aframe-school-gltf-model.glitch.me/solution2.html)  <!-- .element: class="cta-button" -->

---

## Add 3D Models &mdash; Uploading 3D Models

> If you have a model of your own, it can be tricky to upload it to a CDN since
> it consists of multiple files that reference each other. So far the easiest
> way we've found is to dump them into a GitHub repo, publish the repo's master
> branch to GitHub Pages, and use `rawgit.com` to serve them. Alternatively,
> set up Amazon S3. More to come.

------

## Add Tracked Controls &mdash; Add Hand Controls

> Tracked hand controls provide immersion and interactivity with hand
> controllers. In the following Glitch, we've pre-recorded hand control
> movements and button presses with [A-Frame Motion
> Capture](https://github.com/dmarcos/aframe-motion-capture-components).
> Now we just have to add the hands and handle the interaction events.

[Remix Lesson on Glitch](https://glitch.com/~aframe-school-hand-controls)  <!-- .element: class="cta-button glitch" -->

1. Find `<a-entity id="left">` and add the [hand-controls component](https://aframe.io/docs/0.5.0/components/hand-controls.html)
configured to the left hand (`hand-controls="left"`)
2. Find `<a-entity id="right">` and add the hand-controls component
configured to the right hand (`hand-controls="right"`)
3. View the result and see the hands moving with pre-recorded motions

<img class="stretch" data-src="media/img/trackedcontrols.gif">

[View Result](https://aframe-school-hand-controls.glitch.me/solution.html)  <!-- .element: class="cta-button" -->

---

## Add Tracked Controls &mdash; Add Interactivity

> There are many components to add interactivity to hand controls.
> [controller-cursor](https://github.com/bryik/aframe-controller-cursor-component),
> [aabb-collider +
> grab](https://github.com/aframevr/aframe/tree/master/examples/showcase/tracked-controls/components),
> [super-hands](https://github.com/wmurphyrd/aframe-super-hands-component). For
> this lesson, we'll use controller-cursor that acts as a pointing laser for
> each hand. Continue from your previous Glitch.

1. Add `controller-cursor` component to both hands
2. In the `controller-event-handler` component, change the color of the boxes
when they are hovered over with the `mouseenter` event, and restore the color
with the `mouseleave` event

<img class="stretch" data-src="media/img/trackedcontrols2.gif">

[View Result](https://aframe-school-hand-controls.glitch.me/solution2.html)  <!-- .element: class="cta-button" -->

------


<!-- Lessons end here. -->


## Congratulations!

You've graduated from the A-Frame School and now have a virtual uncertified
degree in WebVR.

<img class="stretch" data-src="https://cdn.hackaday.io/images/4174761433219325627.png">

Head to [the documentation](https://aframe.io/docs/) for more guides to become
a master.
