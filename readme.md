<h4>js_queue</h4>

<h5> FIFO queue implementation in javascript </h5>

Takes max_items as numerical input			

<h6>Usage:</h6> 	
	q = new queue(max_items=2);
		
	q.push(1)		// 	returns null   (will return popped item when queue is full)
	q.peek()		//	returns 1 	   (front of queue)
	q.contents()	//	returns [1]	   (full queue contents as sorted array)

	q.push(2)		// 	returns null
	q.peek()		//	returns 1
	q.contents()	//	returns [1,2]

	q.push(3)		//	returns 1
	q.peek()		//	returns 2
	q.contents()	// 	returns [2,3]