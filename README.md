``` php
<?php
namespace QqqReal;

use KeepLearning;

class Developer
{
    private $isHired = false;

    public function isHired(): bool
    {
        return $this->isHired;
    }

    public function techStack(): array
    {
        return [
            Php::class,
            Laravel::class,
            Python::class,
            TailwindCss::class,
            'linuxeye/lnmp',
        ];
    }

    public function needWork(): array
    {
        return $this->techStack();
    }
}
```
 need job hire me for experience...
