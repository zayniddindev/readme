<button>Help</button>

<style>
  .carousel-container {
    perspective: 1000px;
    margin: 2rem auto;
  }
  .carousel {
    width: 200px;
    height: 20rem;
    position: relative;
    transform-style: preserve-3d;
    transition: transform 1s;
  }
  .carousel img {
    position: absolute;
    top: 0;
    left: 0;
    width: 10rem;
    height: auto;
    padding: 1rem;
    border: none;
    border-radius: 0.5rem;
    background-color: #fff;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
    transform-style: preserve-3d;
    cursor: pointer;
  }
  .carousel img:nth-of-type(1) {
    transform: translateZ(0);
  }
  .carousel img:nth-of-type(2) {
    transform: rotateY(90deg) translateZ(6rem);
  }
  .carousel img:nth-of-type(3) {
    transform: rotateY(180deg) translateZ(6rem);
  }
  .carousel img:nth-of-type(4) {
    transform: rotateY(270deg) translateZ(6rem);
  }
  .carousel img:nth-of-type(5) {
    transform: translateZ(12rem);
  }
  .carousel:hover {
    transform: rotateY(180deg);
  }
</style>
<div class="carousel-container">
  <div class="carousel">
    <img
      src="https://user-images.githubusercontent.com/25181517/117447155-6a868a00-af3d-11eb-9cfe-245df15c9f3f.png"
      alt="Technology 1"
    />
    <img
      src="https://user-images.githubusercontent.com/25181517/183568594-85e280a7-0d7e-4d1a-9028-c8c2209e073c.png"
      alt="Technology 2"
    />
    <img
      src="https://user-images.githubusercontent.com/25181517/183890598-19a0ac2d-e88a-4005-a8df-1ee36782fde1.png"
      alt="Technology 3"
    />
    <img
      src="https://user-images.githubusercontent.com/25181517/117207330-263ba280-adf4-11eb-9b97-0ac5b40bc3be.png"
      alt="Technology 4"
    />
    <img
      src="https://user-images.githubusercontent.com/25181517/186884159-4b5e122b-95de-4a32-b10b-7f6fdffa4c5a.png"
      alt="Technology 5"
    />
  </div>
</div>
