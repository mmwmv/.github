## Who are we?

```php
 use World\Countries;

 class MMWMV{

    public String $name = "Mission For Migrant Workers Maldives";
    public String $type = "NGO";
    public String $operating_in = Countries::Maldives;

    public function aboutUs():string
    {
        return <<<STORY
        To be the focal point in the Maldives to advocate for the rights, transform vulnerabilities and actualize justice for migrant workers by following a human rights-based approach.


        i. To raise awareness and strengthen the legal framework, shape policies and designaction programmes which ensure fair regulations consistent with international standards.
        ​
        ii. To safeguard the wellbeing of migrant workers by ensuring equitable access to basic needs and fair living and working conditions.
        ​
        iii. To strive for justice and protect the rights of vulnerable migrant workers by facilitating secure and reliable legal recourse.
        ​
        iv. To lead better data collation and governance on migrant workers for robust research that inform evidence-based policies and regulations.
        ​
        v. To provide operational assistance and coordinate with stakeholders to buildnational capacities and facilitate international, regional and bilateral cooperation onmigration matters.


        Our ethos is built upon five core values that are fundamental to our organisation as guiding principles. We like to call
        it the 5As.
        STORY;
    }

    public function approach():string
    {
        return "We believe in a human rights-based approach where everyone deserves to have their dignity and fundamental rights protected.";
    }

    public function acceptance():string
    {
        return "We respect and celebrate diversity and ensure that inclusion is at the heart of our work.";
    }

    public function alliance():string
    {
        return "We are committed to working in collaboration with all relevant stakeholers.";
    }

    public function accountability():string
    {
        return "We will be transparent in all our dealing and hold an independent neutral stance during matters of conflict.";
    }

    public function advance():string
    {
        return "We are dedicated to innovative research and progressive development of migrant welfare.";
    }
 }

```
