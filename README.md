# Protocols


**Protocols as a parameter type**

protocol ProtocolName {
    var property: String { get set}
}
func protocolFunction(param: ProtocolName) {
    print("\(param.property)")
}


**Using property of protocol in structs**

protocol ProtocolProperty {
    var propertyOfProtocol: String { get set }
}

struct Struct : ProtocolProperty {
    var propertyOfProtocol: String
    var propertyOfStruct  : String
}

struct Struct2 : ProtocolProperty {
    var propertyOfProtocol: String
    var propertyOfStruct  : String
    
    func structFunction(_ param: ProtocolProperty) {
        print("\(param.propertyOfProtocol)")
    }
}
