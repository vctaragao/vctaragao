```php
<?php

namespace Victor/Moraes;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Mova',
                'position' => 'PHP Developer'         
            ]
        ];
    }

    public function getKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            PhpSlim::class,
            Vuejs::class,
            Docker::class,
            GCloud::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Diving deep into Elixir';
    }
}
```
