
[AU 25-26.css](https:[Uploading AU 25:26.html…]()
//github.com/user-attachments/files/24685726/AU.25-26.css)
@media (max-width: 700px) {
  .squad-grid {
    grid-template-columns: 1fr;
  }
}

* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

body {
  background: #ffffff;
  margin: 0;
  padding: 40px;
}

.squad-container {
  max-width: 900px;
  margin: 0 auto;
}

h1 {
  text-align: left;
  margin-bottom: 40px;
  font-size: 32px;
  font-weight: 700;
}

.squad-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  column-gap: 80px;
  row-gap: 20px;
}

.player {
  display: flex;
  align-items: center;
}

.player img {
  width: 50px;
  height: 50px;
  border-radius: 50%;
  object-fit: cover;
  margin-right: 15px;
}

.number {
  font-weight: 600;
  margin-right: 6px;
  color: #0a1f44;
}

.name {
  color: #0a1f44;
  font-size: 16px;
}
