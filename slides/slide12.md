# Components

<pre>
  <code>
  @Component({
    selector:    'hero-list',
    templateUrl: 'app/hero-list.component.html',
    directives:  [HeroDetailComponent],
    providers:   [HeroService]
  })
  export class HeroesComponent {
    constructor(private _service){
      this.heroes = this._service.getHeroes();
    }

    selectHero(hero) {
      this.selectedHero = hero;
    }
  }
  </code>
</pre>
