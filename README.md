<?php
class Animal
{
    public $food;
    public $location;

    public function makeNoise()
    {
        echo "Така тварина спить";
    }
    public function eat()
    {
        echo "Така тварина їсть їжу";
    }
}

class Veterinarian extends Animal
{
    public function treatAnimal()
    {
        echo "Розраховані Їжа $this->food і локація $this->location дана тварина вилікована";
    }
}

class Dog extends Animal
{
    public $name;
    public $age;

    public function makeNoise()
    {
        echo "$this->name спить";
    }

    public function eat()
    {
        echo "$this->name їсть собачий корм";
    }

    public function speak() {
        echo 'woof!';
    }
}

class Cat extends Animal
{
    public $name;
    public $age;

    public function makeNoise()
    {
        echo "$this->name спить";
    }

    public function eat()
    {
        echo "$this->name їсть котячий корм";
    }

    public function speak() {
        echo 'meow!';
    }

}

class Horse extends Animal
{
    public $name;
    public $age;

    public function makeNoise()
    {
        echo "$this->name спить";
    }

    public function eat()
    {
        echo "$this->name їсть траву";
    }

    public function speak() {
        echo 'igigi!';
    }
}
