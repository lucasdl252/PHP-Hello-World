<?php

class HelloWorldTest extends PHPUnit_Framework_TestCase
{

    public function testExpectHelloWorld()
    {
        $this->expectOutputString('Hello, World!');
        require 'hello-world.php';
        $output->hello-world.HelloWorld();

    }
}

