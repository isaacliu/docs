Class **Phalcon\\Validation\\Validator\\Confirmation**
======================================================

*extends* abstract class :doc:`Phalcon\\Validation\\Validator <Phalcon_Validation_Validator>`

*implements* :doc:`Phalcon\\Validation\\ValidatorInterface <Phalcon_Validation_ValidatorInterface>`

Checks that two values have the same value  

.. code-block:: php

    <?php

    use Phalcon\Validation\Validator\Confirmation;
    
    $validator->add('password', new Confirmation(array(
       'message' => 'Password doesn\'t match confirmation',
       'with' => 'confirmPassword'
    )));



Methods
-------

public  **validate** (*unknown* $validation, *unknown* $field)

Executes the validation



final protected  **compare** (*unknown* $a, *unknown* $b)

Compare strings



public  **__construct** ([*unknown* $options]) inherited from Phalcon\\Validation\\Validator

Phalcon\\Validation\\Validator constructor



public  **isSetOption** (*unknown* $key) inherited from Phalcon\\Validation\\Validator

Checks if an option is defined



public  **hasOption** (*unknown* $key) inherited from Phalcon\\Validation\\Validator

Checks if an option is defined



public  **getOption** (*unknown* $key, [*unknown* $defaultValue]) inherited from Phalcon\\Validation\\Validator

Returns an option in the validator's options Returns null if the option hasn't set



public  **setOption** (*unknown* $key, *unknown* $value) inherited from Phalcon\\Validation\\Validator

Sets an option in the validator



