phpsplitchineseword
===================
将单词分割为单字数组

$len = mb_strlen($str);
$words = array();
for($i=0;$i<$len;$i++){
	$words[] = mb_substr($str, $i, 1);
}
return $words;
