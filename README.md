```php
<?php

namespace App\Models;

class Nima extends Human
{
    use InteractsWithHeartBeats,  InteractsWithDifficultconditions;
    
    public function getCurrentWorkplaceAttribute(): array
    {
        return [
            'workplace' => [
                'company' => 'Mdadeh',
                'position' => 'Back End developer'         
            ]
        ];
    }

    public function getDailyKnowledgeAttribute(): array
    {
        return [
            Php::class,
            Laravel::class,
            Python::class,
            JS::class,
            Git::class
        ];
    }

    public function getFutureGoalAttribute(): string
    {
        return 'To contribute to more open source projects.';
    }
}
```


![Nima's github activity graph](https://activity-graph.herokuapp.com/graph?username=Nimaw&theme=xcode)

  <a href="https://github.com/Nimaw/">
  <img src="https://github-readme-stats.vercel.app/api?username=nimaw&show_icons=true&theme=monokai" alt="Nimaw GitHub stats" />
</a>
<a href="https://github.com/Nimaw/" >
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=nimaw&theme=monokai" alt="Nimaw GitHub Github Steak" />
</a>



