```php
<?php

namespace arceus;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'project' => 'Phishield',
                'position' => 'Owner - Head'
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Python::class,
            Javascript::class,
            HTML::class,
            CSS::class,
            Vite::class,
            React::class,
            Flask::class,
            Go::class,
        ];
    }

    public function getFutureGoal()
    {
        return 'idk.';
    }
}
```
