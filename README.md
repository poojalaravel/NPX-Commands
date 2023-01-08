# NPX-Commands
npx create-react-app appMName
npm i react-boostrap  boostrap (Its used to devlop attractive ui)
npm i axios (Its used to send request from client to server OR its used to intract with api)
npm i react-router-dom (rect-router-dom used to make link OR route)
npm i sweetalert--save(its used to show message like error, success, warrning etc.)
After install react-bootstrap then import bootstrap librery in app.js
MAke Menubar
first import librery 


import Navbar  from "react-bootstrap/Navbar";
import Nav  from "react-bootstrap/Nav";
import NavDropdown from 'react-bootstrap/NavDropdown';
import { BrowserRouter as Router , Routes, Route, Link } from "react-router-dom";


function code Add function whatever you want 


         <Navbar  bg="primary" expand="lg">
      <Container>
      <Navbar.Brand href="/"> Basic Crud App</Navbar.Brand>
      <Navbar.Toggle aria-controls ="basic-navbar-nav" />
      <Navbar.Collapse id="basic-navbar-nav">
          <Nav className="me-auto">
          <NavDropdown title="Dropdown" id="basic-nav-dropdown">
              <NavDropdown.Item href="#action/3.1">Action</NavDropdown.Item>
              <NavDropdown.Item href="#action/3.2">
                Another action
              </NavDropdown.Item>
              <NavDropdown.Item href="#action/3.3">Something</NavDropdown.Item>
              <NavDropdown.Divider />
              <NavDropdown.Item href="#action/3.4">
                Separated link
              </NavDropdown.Item>
            </NavDropdown>
        <Link to={"tictac"} className="navbar-brand text-white">
         View Game
        </Link>
        <Link to={"Home"} className="navbar-brand text-white">
        Home
        </Link>
        <Link to={"About"} className="navbar-brand text-white">
        About
        </Link>
        <Link to={"Blog"} className="navbar-brand text-white">
        Blog
        </Link>

        
        </Nav>
        </Navbar.Collapse>
      </Container>
    </Navbar>

