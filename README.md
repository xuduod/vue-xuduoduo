# vue-xuduoduo
pragma solidity ^0.4.21;
 
contract Phone {
    string public model;
    int64  price;
 
    function Phone (string initalModel, int64 initalPrice) public {
        model = initalModel;
        price = initalPrice;
    }
    function setModel(string newModel) public {
        model = newModel;
    }
    function getModel() public view returns (string) {
        return model;
    }
}
