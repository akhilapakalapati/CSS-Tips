# CSS-Tips

# To Remove Link line

javascrit
```
import './index.css'
import {Link} from 'react-router-dom'

const Navbar = () => (
    <>
    <Link to="/" className="link-conatiner">
      <div  className="nav-conatiner">
        <img src="https://static.brandirectory.com/logos/aned001_nz_airnz1.png" alt="logo" className="logo-style"/>
        <Link to="/" className="para-container-nav">
            <h1 className='para-nav'>Sign in</h1>
        </Link>
      </div>
    </Link>

    </>
  )

  export default Navbar
```

css
```
.link-conatiner{
   text-decoration:none;
}

.nav-conatiner{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    background-color:black;
}

.logo-style{
    height:75px;
    width:190px
}

.para-container-nav{
    text-decoration:none;
}


.para-nav{
    color:#34dbeb;
    font-size:20px;
    font-weight: 400;
    padding: 5px;
    text-decoration: none;
}
```

---------------------------------------------------------------------------------------------------------------------------------------------
