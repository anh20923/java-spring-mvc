error id: file:///C:/Users/Anh/Desktop/HoidanIT/Java%20backend/2.1%20Java%20MVC%20-%20code/01-java-spring-laptopshop-starter/src/main/java/vn/hoidanit/laptopshop/config/WebMvcConfig.java:_empty_/ViewResolverRegistry#
file:///C:/Users/Anh/Desktop/HoidanIT/Java%20backend/2.1%20Java%20MVC%20-%20code/01-java-spring-laptopshop-starter/src/main/java/vn/hoidanit/laptopshop/config/WebMvcConfig.java
empty definition using pc, found symbol in pc: _empty_/ViewResolverRegistry#
empty definition using semanticdb
empty definition using fallback
non-local guesses:

offset: 883
uri: file:///C:/Users/Anh/Desktop/HoidanIT/Java%20backend/2.1%20Java%20MVC%20-%20code/01-java-spring-laptopshop-starter/src/main/java/vn/hoidanit/laptopshop/config/WebMvcConfig.java
text:
```scala
package vn.hoidanit.laptopshop.config;

import org.springframework.context.annotation.Bean;
import org.springframework.context.annotation.Configuration;
import org.springframework.web.servlet.ViewResolver;
import org.springframework.web.servlet.config.annotation.EnableWebMvc;
import org.springframework.web.servlet.config.annotation.WebMvcConfigurer;
import org.springframework.web.servlet.view.InternalResourceViewResolver;
import org.springframework.web.servlet.view.JstlView;

@Configuration
@EnableWebMvc
public class WebMvcConfig implements WebMvcConfigurer {

  @Bean
  public ViewResolver viewResolver() {
    final InternalResourceViewResolver bean = new InternalResourceViewResolver();
    bean.setViewClass(JstlView.class);
    bean.setPrefix("/WEB-INF/view/");
    bean.setSuffix(".jsp");
    return bean;
  }

  @Override
  public void configureViewResolvers(ViewResolve@@rRegistry registry) {
    registry.viewResolver(viewResolver());
  }
}


```


#### Short summary: 

empty definition using pc, found symbol in pc: _empty_/ViewResolverRegistry#