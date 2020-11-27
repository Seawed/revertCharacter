
$phrase =  'som@3e teADxt';
function revertCharacter($arg)
{
    return $x = strrev($arg);
}
echo (revertCharacter($phrase));
echo('========');
if (revertCharacter($phrase) == strrev($phrase)){
    echo ("if you see that message, unit test passed");
}

