# array_multisort_value
<pre>
$array = [
  [
    'goal'  => 'sortableValue',
    'other' => 'value'
  ],
  [
    'goal'  => 'sortableValue',
    'other' => ''
  ]
];
$result = array_multisort_value($array, 'goal', SORT_DESC);
</pre>
