# add-function-reset-draft-11
function resetMyGarage() external override {
        delete garages[msg.sender];
    }
