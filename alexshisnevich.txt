1.


    for (y = 3; y <= map.getHeight() - 10; y++) {
        map.placeObject(3, y, 'block');
        map.placeObject(map.getWidth() - 5, y, 'block');
    }

    for (x = 5; x <= map.getWidth() - 5; x++) {
        map.placeObject(x, 3, 'block');
        map.placeObject(x, map.getHeight() - 10, 'block');
    }


2.

/*

*/

3.


    for (y = 10; y <= map.getHeight() - 3; y++) {
        map.placeObject(5, y, 'block');
        map.placeObject(map.getWidth() - 5, y, 'block');
    }

    for (x = 5; x <= map.getWidth() - 5; x++) {
        map.placeObject(x, 0, 'block');
        map.placeObject(x, map.getHeight() - 3, 'block');
    }

4.

 for (y = 7; y <= map.getHeight() - 3; y++) {
        map.placeObject(11, 12, 'exit');
        map.placeObject(map.getWidth() - 3, y, 'block');
    }

5.

             if  (i>40)
             {i=76}
             map.setSquareColor(x, y, '#fff');

6.

    map.placeObject(map.getWidth()-20, 7, 'block');

7.

        var player = map.getPlayer();
        player.setColor('#f00'); //red
        if (player.atLocation(30, 12))
       {player.setColor('#0f0'); // green
       }

        if (player.atLocation(27, 12))
       {player.setColor('#ff0'); // yello
       }
        if (player.atLocation(36, 12))
       {player.setColor('#ff0'); // yello
       }

8.

generateForest

9.

    map.placeObject(2, 4, 'block');
    map.placeObject(3, 4, 'block');
    map.placeObject(20, 16, 'phone');
    map.placeObject(20, 17, 'computer');

    map.getPlayer().setPhoneCallback(function () {
        var player = map.getPlayer();
        if (player.atLocation(20, 14))
       {player.setColor('#ff0'); // yello
       raftDirection = 'up';
       }
    });
  
10.

            moveToward(me, 'player');
            map.placeObject(1, 12, 'block');
            map.placeObject(2, 12, 'block');
            map.placeObject(3, 12, 'block');
            map.placeObject(4, 12, 'block');
            map.placeObject(5, 12, 'block');
            map.placeObject(6, 12, 'block');
            map.placeObject(7, 12, 'block');
            map.placeObject(8, 12, 'block');
            map.placeObject(9, 12, 'phone');
            map.placeObject(10, 12, 'block');
            map.placeObject(11, 12, 'block'); //central
            map.placeObject(12, 12, 'block');  
            map.placeObject(13, 12, 'block');  
            map.placeObject(14, 12, 'block');  
            map.placeObject(15, 12, 'block');
            map.placeObject(10, 11, 'block'); // sopper
            map.placeObject(30, 12, 'block'); // for green
			
89 line =         me.move('right');

11.

var j = getRandomInt(1,4);
if (j%2==0)
{
me.move('right');
}
else 
{
me.move('down');
}			

12.

        if (me.canMove('right')) {
                me.move('right');
                 map.placeObject(5, 1, 'block');
                 map.placeObject(5, 2, 'block');
                 map.placeObject(5, 3, 'block');
                 map.placeObject(5, 4, 'block');
                 map.placeObject(20, 5, 'block');
                 map.placeObject(19, 6, 'block');
            } else if (me.canMove('down'))
            {
                me.move('down');
            }
            
            else  {
                me.move('up');
                
            } 
			
13.			

            map.placeObject(30, 15, 'phone');
            if (player.atLocation(31, 15))
            {me.move('right');}
            else
             if (player.atLocation(29, 15))
            {me.move('left');}
            else
             if (player.atLocation(30, 16))
            {me.move('down');}
            else
             if (player.atLocation(30, 14))
            {me.move('up');}
			
14.

TheAlgoritm

15.

exit			
			
16.


49 line =    ctx.strokeStyle = color;//'white';


  map.placeObject(1, 1, 'phone');
  map.getPlayer().setPhoneCallback(function () {
        var player = map.getPlayer();
        var colors = ['red', 'yellow', 'teal'];
        var i = getRandomInt(0, 20);
        var color = colors[i % 3];
        player.setColor(color); 
     
        });
	
17.

solved by luck with teleport =)

18.


     for (var i = 20; i < 30; i++) {
            map.placeObject(i, 12, 'phone');
        }

19.

random click right left and down	
		
20.

   map.placeObject(25,9 , 'block');
    // map.placeObject(25,20 , 'theAlgorithm');


     map.defineObject('bullet2', {
        'type': 'dynamic',
        'symbol': '.',
        'color': 'yellow',
        'interval': 100,
        'projectile': true,
        'behavior': function (me) {
            me.move('up');
        }
    });



  map.getPlayer().setPhoneCallback(function () {
        map.placeObject(25, 8 , 'bullet2');
		
        });


		


			