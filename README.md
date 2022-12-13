# Game Development Scripts Unity
Some scripts for game development in Unity

* Basic Character Movement 2D


```
   public float speed = 5;
   
   void Update()
   {

    	float h = Input.GetAxis("Horizontal");
	float v = Input.GetAxis("Vertical");

	Vector2 pos = transform.position;

	pos.x += h * speed * Time.deltaTime;
	pos.y += v * speed * Time.deltaTime;

	transform.position = pos;

   }
```
