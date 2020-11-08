@Component作用在类上，当启动应用时，Spring会自动检测并配置被注解的类; 而@Bean是方法级别的，需要在配置类中使用，即类上需要配合@Configuration注解才可以作用在方法上，可以按需选择注入的方法，所以更加灵活精确的在需要的位置配置bean。
此外，如果想将第三方的类变成组件，当没有源代码时，无法使用@Component进行自动配置，此时就可以使用@Bean来进行配置。
