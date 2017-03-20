extension UIImage {
    
    static func defaultHamburgerImage() -> UIImage {
        
        UIGraphicsBeginImageContextWithOptions(CGSize(width: 20, height: 13), false, 0.0)
        UIColor.black.setFill()
        
        UIBezierPath(rect: CGRect(x: 0, y: 0, width: 20, height: 1)).fill()
        UIBezierPath(rect: CGRect(x: 0, y: 5, width: 20, height: 1)).fill()
        UIBezierPath(rect: CGRect(x: 0, y: 10, width: 20, height: 1)).fill()
        
        UIColor.white.setFill()
        UIBezierPath(rect: CGRect(x: 0, y: 1, width: 20, height: 2)).fill()
        UIBezierPath(rect: CGRect(x: 0, y: 6, width: 20, height: 2)).fill()
        UIBezierPath(rect: CGRect(x: 0, y: 11, width: 20, height: 2)).fill()
        
        let defaultImage = UIGraphicsGetImageFromCurrentImageContext()
        UIGraphicsEndImageContext()
        
        return defaultImage!
        
    }
