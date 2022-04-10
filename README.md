![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=Zooxv&hide=contribs,prs)
<?php

namespace Cenzoo;

class About extends Me
{
    public function getCurrentWorkplace(): none
    {
        return [
            'workplace' => [
                'company' => 'zx.corp',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            ReactNative::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
        return 'starting afifahh operating system'
     
