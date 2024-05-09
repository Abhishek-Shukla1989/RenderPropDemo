This demo explains how to pass components as render props inside other components. 
        {isOpen && <WrappedComponent {...props} items={displayItems} />} //  Line 23 under HOC.js received props as render components.


   In react at many places we need to pass components as props and render them inside other component and manage state outside/parent component. 
   const ProductListWithToggles = withToggles(ProductList);
   this component created a renderer to display and toggle list inside other component.
   
