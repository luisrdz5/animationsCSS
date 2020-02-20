# Animations CSS
Documentation about CSS animations

- Transitions
    - transition
    - transition-property: width;
    - transition-duration: 1s;
    - transition-delay:1s;
    - transition-timming-function: ease;

example: 
    [link](./examples/transition.html)


- Transformations
    - transform: rotate | skew | position | scale (rotar | Sesgar | posición | tamaño )
        - transform rotate
            - transform: rotateX(deg)
            - transform: rotateY(deg)
            - transform: rotateZ(deg)
            - transform: rotate3d(x, y, z, rotate);
        -transform position 
            - transform: translate(x)
            - transform: translate(x, y)
            - transform: translate(x, y, z)
        -transform scale 
            - transform: scale(x, y)
            - transform: scale(0 = 0% del tamaño - 1 = 100% del tamaño)
        -transform skew(sesgado)
            - transform: skew(x, y)

examples: 
    [link](./examples/transforms.html)


Note: You can change the origin of the transformation 
- Transform-origin 
    - examples: 
        - transform-origin: bottom;
        - transform-origin: left;
        - transform-origin: 0% 50%;
        - transform-origin: right;
        - transform-origin: 100% 50%;
        - transform-origin: 75% 75%;
        - transform-origin: x y;
        - transform-origin: top;

- Animations
    - animation-name: cuadrado
    - animation-duration: 1s
    - animation-timing-function: ease-in
    - animation-direction: reverse
    - animation-fill-mode: forwards
    - animation-play-state: running
    - animation-iteration-count: infinite
    - animation-timing-function: ease

    - Animations (acceleration and bezier curve )
        - animation-timing-function: cubic-bezier(.75,-0.31,.33,1.4);
    Note: to get bezier curve examples visit [cubic-bezier.com](https://cubic-bezier.com/)

- Web Animations API (JS Animations)



- Animations Types

- Animations in ReactJS
