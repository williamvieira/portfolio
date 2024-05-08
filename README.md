```php
<?php

namespace WilliamVieira;

class About extends Me
{
    public function getPersonalInfo(): array
    {
        return [
            'name'     => 'William Vieira',
            'position' => 'Full Stack Developer',
            'location' => 'São Paulo, Brazil 🇧🇷',
            'website'  => 'https://williamvieira.tech/'
        ];
    }
    public function getSkills(): array
    {
        return [
            'languages'  => ['HTML', 'CSS', 'JavaScript', 'TypeScript', 'PHP', 'C#'],
            'frameworks' => ['VueJs', 'React', 'Angular', 'Laravel', 'WordPress', 'CodeIgniter', 'Ionic'],
            'databases'  => ['MySQL', 'PostgreSQL', 'SQL Server'],
            'versioning' => ['GitHub'],
            'containers' => ['Docker'],
            'cloud' => ['AWS', 'Azure', 'Cloudflare']
        ];
    }
}
```

---

You can reach me via [Linkedin] (https://www.linkedin.com/in/williamvieira-tech/) [Portfolio] (https://williamvieira.tech/)
