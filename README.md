Basic and to-remember:


GREEN: #00963C
BLUE: #2981ca

max width = 730 px

TODO:
*paprasīt Naurim visas foto. Foto ir:

1. Vitamīnu tēja (2928)
2. Amora bulta (2931)
3. Balles karaliene (2933)
4. Bērniņu tēja (trūkst!)
5. Cukurpaska (2937)
6. Dziesmu vācelīte (2939)
7. Tēja lunkanumam (2941)
8. Mērenības tēja (2942)
9. Pirts tēja (2946)
10. Rozīt' mana nātru dārzā (2948)
11. Saulesstars (2950)
12. Spēka tēja (2953)
13. Svētku tēja (2954)
14. Vakara tēja (2956, 2957)
15. Vēdera prieki (2958, 2960)
16. Vesels kā rutks (2961, 2962)
17. Vīru tēja (2963, 2964)
18. Ziedu karnevāls (2965, 2966)
19. Tēja ugunīgām sievietēm (2967, 2968)
20. Ripoja akmens (2969, 2970)
21. Ziemas Svētku tēja (2971, 2972)

trūkst foto no šādām tējām:
Bērniņu tēja (iekšā rudzupuķes)
Saulesstars (ļoti dzeltena)
Spēka tēja (asinszāle, sarkanais āboliņš)
Rozīt mana nātru dārzā (ļoti rozīga, daudzrozes iekšā)
Pirts tēja (ar auzām un kumelītēm, bet citādi līdzīga vakara tējai)


* fitri:
Viss klāsts
Jauktās tējas
Mono tējas
Citi produkti

Viss piedāvājums

Tējas
  Jauktās tējas
  Mono tējas
Citi produkti
  Pinduļi
  Skrubji
  Pirts slotas

---------------------

hexo generate && hexo server
-------------------
# comment:
[CTRL]+[K],[C] = Comment the current line, or selected lines of code

[CTRL]+[K],[U] = Uncomment the current line, or selected lines of code
---------------------
# cart button:
at the end of file: post-full.ejs


    <% if (item.price) { %>
      <div class="buy-button text-center mt-4">
        <button class="snipcart-add-item"
          data-item-id="<%- item.id %>"
          data-item-name="<%- item.name %>"
          data-item-price="<%- item.price %>"
          data-item-image="<%- url_for(item.image) %>"
          data-item-url="<%- item.permalink %>">Add to Cart</button>
      </div>
    <% } %>
----------------------
# theme guide:
https://sharvaridesai.gitlab.io/hexo-theme-milan/install/

new post:
hexo new post "Tejas nosaukums"

herbal-tea icon:
https://www.flaticon.com/free-icon/herbal-tea_89169#term=herbal%20tea&page=1&position=27

Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)