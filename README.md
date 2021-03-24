```php
<?php

namespace Victor/Moraes;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Incluir Tech',
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
            Vuejs::class,
            Docker::class,
            Kubernetes::class,
            GCloud::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Have a try of Express and Django/Flask';
    }
}
```
