# mousehover
JQUERY: НАВЕДЕНИЕ КУРСОРА НА ЭЛЕМЕНТ

Для примера отслеживаем средствами jQuery наведение на объект дерева DOM с классом obj.

<pre>
<code>
$(document).ready( function() {
	// 1 вариант
	$(".obj").mouseenter(
	function() {
		// навели курсор на объект
	});

	$(".obj").mouseleave(
	function(){ 
		// отвели курсор с объекта
	});

	// 2 вариант
	$(".obj").hover(
	function(){ 
		// навели курсор на объект
	},function(){
		// отвели курсор с объекта 
	});
});
</code>
</pre>
